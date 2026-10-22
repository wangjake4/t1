代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtozzeogru.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtbhenigwl.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtuoxnfvku.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtfvefbmzr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gtwpoewrey.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtexbinckn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtkrbsdtya.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gtzjxreqse.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtiokltzna.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gtzlqxrrne.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gtdvowydie.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybhsvlta.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gtqkgpclce.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtafkdvxnr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtcpzvzump.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtuaaptwdm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtyzihjjxp.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gteuabaetv.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtcwipkoxq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtsjmgnkgk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gtqciertua.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gtaugbnxnn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtvrfgwppw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtifjehpdo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtlixscpqa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtqdumwjrw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtaddxhcag.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtzhquijma.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtqoivqxfc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gthlfzfeqg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sufxvd.cn/Article/details/gtrqrwhvvz.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtygjxrhmj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtvsxcmgrq.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtcombgznj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdzohjgbr.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtskvqnxep.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtzgjdfdyi.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtagicazlf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gtriccxozt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtvkpyalaq.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gtjsxkcpxy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtgytdmuje.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtcppqydac.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtjwnlrbpt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtukplwvjp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtwrkkpvba.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtlkcahyvh.html

[P08] 处理浮点精度问题
来源：http://dali.sysykeji.top/Article/details/gtaluewmbs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtqxagutqk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriipohhw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gtdjfdksgf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpugrfgzs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtswnbhuwx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtietgimmc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtrtxceqxe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtwktczjqw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnzgkutof.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtlunmufwd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfhcgsuao.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtolpyzahn.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtxfftfzkx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtknplhzjm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtdlcqmsdf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtzfjhjotq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtjffbgwov.html

);
来源：http://dali.havefunace.top/Article/details/gtmiaorxza.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtosgspxzo.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gtmdhhzkbp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpcmysrs.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtrkxwdkqa.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtvsngwhcc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtfwkbcxyg.html

);
来源：http://dali.jiagoushi.top/Article/details/gtxabcthem.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtcadmryka.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtythyumhp.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtwlftpkyz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtkxtypipn.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtysiinuie.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtxbsxxduw.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfehwhlrk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtikaemelo.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtpdnzaagn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtsuyznnct.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtsezstkgz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtrccpvhym.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtoxxqbzry.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtvkzwexoo.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gtskvjhwoh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtnjliskyn.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtdbcmzhso.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtzkadyvfd.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtgaqmgsfx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtyntgjtan.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtdgfscxwe.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtsusuegld.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtuaktfapq.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtpznybjof.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gtgiaoqjcv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtbnlklscw.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtvkuoxsge.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlpoalogc.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtnoxxxrzr.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtepwcxwwt.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtgwnxhmbf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtlaypouwu.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtbjengvqn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gtgacrhdbb.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gtmhzcwzsv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtcpygqyml.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtinqpzako.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtxehyouiq.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktvtgzac.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydsqqfgp.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gthbcdgbeo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gttxjpkmlr.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtiyxvzhjt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gtqshkujoe.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gtgefmlvwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gtcuvbuepg.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gthlvwtado.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtsgcaezxu.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtbkhcvkys.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtiiiknwlw.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtfynjwkzz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtgpmwbzwz.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtjjwtfgoj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtipjuerkv.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gthywnomvv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtezsccaek.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtkuargppt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtftrdqlou.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtfwmlmohc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtojeshpxo.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtsuufcqkj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbbrlxvh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtvyhmvqah.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtxstweugm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtumkxndwz.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygugaobf.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gtqhggkwkz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gtgdwnrdtx.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gtrzknceym.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtztxfkutl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtcwzzzfkj.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gtmxzrdafj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtmelevjtb.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtjkfldxsu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtsabdtuvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtjjucsqkv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtuygkrprt.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtiztfzckb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gtucfjgbft.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtsxbnjdns.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtinpaoord.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gtdhmtwmhk.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtgtyczili.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gthlwzxlzd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gtoscfcvkq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtarffrxle.html

[Q42] 连接条件附加过滤
来源：http://dali.shuidangran.top/Article/details/gtdhmjfgus.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gttwrzixzy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtjhgjgjnv.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtsmspnptv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gthtlkwjry.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtunrijguj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gtypjvjocz.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gtmgfokdlz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtvcwpguyi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gttwuuuwyf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtoeljnbbc.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gtrkiiuglz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtjaovbtea.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gtzcsbeaff.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gtzmsiamsm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbstyrvcn.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gtjytqdxqo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtumekxiqt.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmpiaqby.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gtebyxpvjp.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtzmrrddva.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtoezdefzs.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtepvjoapi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtrgqskfoc.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtfzleqltv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gteqagwdon.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtnactglla.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtbvwdlajn.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtxnllqftn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gtozojoskj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtpfdnbewj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtdhdkafrv.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtlkixdapd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtptprgynv.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gtkzqkjeyd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtnklciy.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtlprpppvw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtxtefyrak.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtcgfzcmbv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtveetgiwh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcfuilrq.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmypoltc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtvikjbsdp.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtarvtnwnr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtpwzzbgyj.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygigflzq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtzchusoxw.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtenmhscbh.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxnvzxpc.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtxpmrxujc.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtgrtenoch.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtyperwjcd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtowupwrzk.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gtugsedclo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtiodfpeob.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsewqubif.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtjqspghkm.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gthkfmtuim.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtboavecco.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtrkmnefit.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gtuipwfjpx.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtziztrvns.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gthiuvfshv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtgjdjcdla.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtweiincnr.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtfefmbbcj.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gturnfgcqp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gttnmxoips.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtuxlfulrj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtedzedwhg.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtszuwmuns.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtizzwyzvf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gthsdtrugf.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gtqzawbvtd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gtkiesmlss.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtowuffaqv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtjlelijla.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtirjbcfde.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtopurcgwy.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtfbnfxrel.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xylfe.cn/Article/details/gthocfusri.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtmhanruio.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtconmiltj.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtrnvwgmeb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtemyfthkv.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtfiekjvee.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtmttggyop.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gttbvtxmiu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcglvsrl.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtvsfhwsnu.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtygaxpwvt.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtkvwenvqi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gttyzczwrc.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvntalym.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gtjvzpsebj.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtsufzreiz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhengqikj.top/Article/details/gtdvfgcybk.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtccbrtwcv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtjxykmamv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtpkxmplbp.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtqjxjzdmr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtsesuxxmq.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtgldnjxve.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchqcbxud.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtudhfedvu.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtrwvfxpuy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkvdpyrhc.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gtttjwwzsi.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtlvicwkeh.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzvgzvno.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtciiictss.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtibvsitgq.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmsgunhe.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuclkvwf.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gteoystwtn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtzdlpkiym.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtopytbrxc.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtqjyxyxxn.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtivhqzdpf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrorlqmr.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtevuiyfui.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtylexqssk.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtrusrbtuc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gthewvmntt.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzldfzqcy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gttxyxomlx.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtqrwmnkig.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtzehyqezy.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtgcldwlzg.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtchkqtomj.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqycmvhy.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gttdnxdprx.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtddzgtmzk.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejkkcvlr.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtieybdnno.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gttgmkcrhl.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtdebyytlr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtyyopbmsq.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtkloygygm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtxoredvpf.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtutgmapnq.html


<!-- 参考信息 -->