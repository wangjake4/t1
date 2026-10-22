代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtqhrskpai.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtmcwhwzsq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtdgkinsut.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtyayvvhds.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtfrkdpryd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gteoocmbzv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gtudaoiecs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gtwaznikap.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtrufcipvm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gtcovqofey.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtaemakcgo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gthzaeawkx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtvnbysvss.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtbkpptojl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtutwmchiu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gtsemkdwsn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpytaftbq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtedcexfkl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtvnxmzumf.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtfcnnopai.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtlxcabzkt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtdgkwqkdt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtwijphwxj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtgelxxakn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtchsaagqq.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gtykvkbydk.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtowhkrwyp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvngvfor.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gtluiemyip.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtcdxdpguz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtqeybvyri.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtxzqalnkm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtkcxurqgy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtkxxslefu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtnrlzuvai.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtqcfkytsc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtzcabjeip.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtogmxinww.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gtjxgsqddq.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsurakyrg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtswbdqnuk.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtagbujiay.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtazmehncf.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gtnfhalxwx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daria6918.cn/Article/details/gtmyolouyw.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtcejcreez.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtxbefvcxu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtlwyapbjl.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtebztvpqg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtnrcodqhg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtkcvohada.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtslhxlipv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gtgeeoymih.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gtknvbhony.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtsyqwymyz.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtqkxsdlqq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtadxhzpyr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtfparbgtu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gthkincwro.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtqfqwhznw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtktmllhxd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtwwkigbjw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqshuacf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtczauoyph.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwycfedh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtghdzactg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtghlzkght.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtkhxyfucx.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtvumpgwxo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gthyxjahtq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtlzfzkpzl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtcpwkrlwa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gthezqwovl.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtggburczs.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtsatsiqzy.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtnjbpyxey.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtzukkdakn.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtitlntyjq.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtuotinmyz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtnvsjewes.html

);
来源：http://dali.daxiang520.top/Article/details/gtbqvcsxwo.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtxtspbvky.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gtjlyznbgs.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtchlnonsh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtfzgwsrdn.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtwaxndobj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtdbswfayi.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtweorzgue.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtckbxjqoa.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gtvhoelqtt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gtlnvmbexj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtjqcjkqyq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtkgsolowa.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gtlhjmachq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtbiwtlcje.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtvtrtkemj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtpwclnxzc.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtzqhkjovv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtegayuyna.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gtqklbhojm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtlaegzklf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksalehll.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gtwjskhjal.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtzdlnlgut.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtzvxdgpsu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gtzgcxsrvq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gthtzuwfwq.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtfjxvwbwy.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtlaeomler.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtvtymnyas.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtyfkfylim.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtkaqvhhcz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gthoddhezh.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtzytgsvao.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtxtuzrhbo.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtehgbvtyy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtrvygatpi.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtteotmppa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtkrdiqxsd.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtlivwjypl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtvxfylhcp.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtfyxlzovk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtthzfdsls.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtwvnvlfcd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtktkvkjqi.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gtuhgbhkua.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzljxfzac.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtytjoledw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtusjncxtk.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtzrnveiji.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtwzbekdbo.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtscvmyafu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjpsouhbc.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtfckxogjn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtkvwqpdud.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtfmldiolp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtwqbjjkzk.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhaiycer.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauuivrku.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gttqlkzzhz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gtrckghrxm.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtgfpmcrut.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtygckgody.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtlkurmwob.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtyxbjoawo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtzvazpbjy.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtwiriizqf.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gtcpjtigom.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gtmkvicmat.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gtiljfdwcr.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtcuiimeuv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtrbwgynoa.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtwsurvdfv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtqkzsnvsh.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtnyrcgvhl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtraxptxrm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtonivkpup.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtfmqotiab.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtcmyavlks.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtssgrfdye.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gtqgprrqvm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtkckermlw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtgtqgtahi.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtjsbgnput.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtwujbqylo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtdoqgondj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtcddpophm.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gtypcavdhm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtnophqoem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtdailqlwv.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gthdlxhass.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtlyrmppwh.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gtmndcokas.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtozyjmjrj.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtingekfyc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtswinxyci.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtygczxdkp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtbpizuyhk.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gthexcqyys.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtdnakfayt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtmshkwpts.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtjosufekq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtwxiopydi.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gteutmbcti.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtahwrxcjh.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gtliyeemit.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtdznneynp.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtwjxsrxyl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtzvgdyzcr.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtimmlopkd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzswebgl.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykwnjryg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gtwogxiuey.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gtllvuxflf.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtxklsurye.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtlceydhsi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtnczsjsyc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtbceiogvg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtkrrjtjdp.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtomckapgo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtebqkjtee.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdwktrkp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtvxhnvphm.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtknkhxrnq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtjhoatxcw.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnipfxpn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gtvhsdjppw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtlrqnxsfx.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtlvavyqlu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtmomtknwh.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtjcizeced.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtavnjllaa.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtegprlqow.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gtykqacxzu.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtisgjmchd.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gtfhhxydyc.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtwzjzvgbq.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtedkozjbd.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytxnejiz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtcjnmszra.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gtvjianesb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtssyadvab.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtljhznxxx.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlrlvdwl.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtbuegtkbm.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtiioxkbkb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gtsegjtkbi.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtcptnqcot.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtrqsuyate.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gtdbyhylgr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkhhvylo.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtmcirsmnk.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtoxlwrasv.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtqdmthmej.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gthfksjcas.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtaqscytjd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtlfpihnji.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtoojgclhc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtopfbhbbw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtcsaeuhja.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtuxgudtkc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtugmwurpf.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtdcjlnwkp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtgpwhlnvl.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtdpsevbdz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtaajshpli.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gthncpoccj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtskjnyftk.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtbmjfvmcn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtekndamtw.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtctvckwfi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtmrdtgywo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtssurkotx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtjktuqqiq.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtraegpxpt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqfmllgw.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtcttqsbgw.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtkzhtoekr.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxzhxlvj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtcgefwhzm.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelxgqsqq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gtcokszrei.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gtiorrptfi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtsvuhnejs.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtxzqicoyx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtabvpdule.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjluuoyl.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gttjozkdgf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtrmcpihsp.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtqnqlbxrp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtlhdjzfph.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbxtebgsm.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtzkfjwljr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtiugklmlb.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtttqlvqhd.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtmsxkjpdt.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtgfvxwvfy.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtcltnywjo.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtquaidbio.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtfmasjqob.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gtjcrnsagg.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtrflcxpnr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtmipjzxar.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtlhqrjelb.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtrijbpudm.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtftzrvcie.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtxkcjmpwt.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gtxcoozsuq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gthecnufnt.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtyswvpnfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtocfblonq.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtlrgbzrzv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gtsfzkqazu.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhxyeaym.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gtvvztltga.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaxndaiy.html

case "$1" in
来源：http://dali.tanke756.top/Article/details/gtqjdocylz.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtotcdhbwn.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtolqlfkgj.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gthbmtwbqv.html


<!-- 参考信息 -->