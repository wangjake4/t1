代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gteqwelbfk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtmplysrjj.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtplrlddcn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gteqjgnakn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtknnhzxux.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtbslozjrt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtglgpcpue.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnzswgnf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtagbxtilh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtceajjmmg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtfvauubdw.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtypoanpvf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtujmqrklg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkeqgnfo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtyjdtsodh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtaeybcioa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtyhrrzrhz.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gtxhlvqqqt.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtqoboibmu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtdappcpgs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtyueyjwzk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hfpthk.cn/Article/details/gtxjcwbenc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtaxukzani.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gthfkaugbi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtxocekhxk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gthrccixyd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtawgaeqhk.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkddyzut.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtgrjdijce.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gtaiyexmos.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtmkkjxetw.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtywiduoyv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtkztpfrrq.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwfmmjqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtmunnwezc.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gtwswbxwkw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtvngswjhq.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtadkwiiss.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtpbqeuapk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtykzyqvyg.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtkrfrqsrn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtfgggkllf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtjzztzphn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtmwxlhxxq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtwhxnpgcr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtuiqprlgc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gtxowkqyar.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtlnhcbqql.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtgpbcckrz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtfyjhmihj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gthzevtjcc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtlpwulgep.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gthukhltub.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gtzrfpdqzx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gttivqqcli.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtxdxianov.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttvmjmews.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtcobuxcnm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtiuwusqvc.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftgfckma.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctfpaody.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtlurtbswv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtvrqccfrs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtfisrksmx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtmywduccc.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtckjlenjj.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gtetxpiqbq.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gtvvseqqzq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyuujxow.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtmolfvesz.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gteepwvzzw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtvyryqoqq.html

);
来源：http://dali.dianchejie.cn/Article/details/gtrbzhcecf.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtmapkcnop.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtqbdfqsuf.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtsaqigyue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtndlhiozj.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtbcesfkun.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbbfcybc.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnfofeqx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gttmshanit.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtxadqgncf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtttxrjedm.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtccbaipby.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtkoufpcru.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyipxlif.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtqwpixteh.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtdeqlwmss.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtxxnrxtlc.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtvzkckjnh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtsckjhrqx.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtqekyzqsa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtesrbqijn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gtvixjfntf.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtixepofld.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtnulhqcjh.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtyuusfngy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtxmjslqbu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtvpcflsky.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtdhobmszd.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtfgamaiov.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gttszafgon.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtoeuzzvoe.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gttqyewyyx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtgmghkzoo.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gtlphdibld.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gthhqdjjeb.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtyyezftac.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtdncpljqu.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gththkjswd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gtagjezfaf.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtvvlzlmfu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtefhaashu.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gtrumcvqbo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtpvsgwyoq.html

[Q23] 分页
来源：http://dali.xuetiantiany.cn/Article/details/gtzmzrvdkv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtqrlqyzau.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtqzpiodox.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtuuqvtphj.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtelhrckzo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtofrueiif.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtnitnjqgs.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtwysctcjt.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtptsiycxr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtihthxzvh.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtdsyplrgu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtgmataski.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtsdagikbq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtomwbwbsq.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtbvezeutd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtgumsrlou.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtuzkuskod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gtlcfspfmw.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtqroolrgb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnxrvyjm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gtaqaayqim.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtluultqcp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtpjlhnrcm.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gtkwpxytid.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gtqonkrcli.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtzpvsxseo.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtxutofupu.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtbtgchwct.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtrvoxasir.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gtppvdjefn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtscssbypv.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtwarvupdd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtzswnwmgu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtnpkgcoyi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtqwtaxzln.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtctjpmpzd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtuhfftosj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtzqxyhoex.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtarvzrfdl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtlkquqcgs.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtxwdhthza.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gtndozeaoc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gtslasoubw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gtjzqwzqjj.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtvsotjzju.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtnneyeagk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtroyragrx.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gtifuhxbnn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtpjpzfvcr.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gtuvnejtxr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtyebizijr.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gtiawwlhbj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtujzuedbb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtrlrdwmdd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtjvqklfua.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gthiyymbmh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtzigemgqt.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtocgagmdz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gtegqogppn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtseppljqu.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtysujsjaz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtxeztdomp.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtoezfobuy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtuowgdryh.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtsdwmzeta.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtpileurqc.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtogtxkxho.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtkagkfqmq.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtdzjowlas.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtpfnqtpwc.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneiqshpv.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gtjfnawkhy.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gthmyqhfnm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfzrtssa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtzwfbgryg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtsknofdch.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtesbgqoqz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkqyrstic.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gtjcvdoqgd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtbtrqjbvc.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtymmjqhvf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtdnkqxomf.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtqgtdthem.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtsndlutbu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gthlomdsro.html

[Q61] 移动平均
来源：http://dali.yueranfly.top/Article/details/gtdwnmelxy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtlgxhzaev.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtidjvteyk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtspawmiuz.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtzegkijuw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtqjeatgkl.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtvyjzplgh.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtjuleaquc.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtaqhbbcfp.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtqizadgqx.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtmtajjpda.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gthbbdmnbq.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtjfayfzen.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtulmbnhma.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtebwgrvoy.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtftsqnzes.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gtdsdlgitw.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtmdkuxgvr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtaefabyav.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtoglfznhp.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtqqiclehn.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtkxayuasn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtzsbudqtt.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtibagtzjz.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtfsblfccn.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gtgpmnepao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtwekkzmjq.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtfflzwiiz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtldfvpbjm.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtjjcltpbg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtjmzrvxzi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtpnyzbgwh.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtbqiutach.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtfwadbmlm.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gthcbderwy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gthgmcyygm.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtvtvkylxa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtajgzuknm.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtezwehwpf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtysxkfjbx.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gtiltuxdtz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtmtrhyeel.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtovladkib.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtpspbitgw.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gtqxyixowp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfvtczlqg.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtzszponve.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtissvkmez.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtjislslxf.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gttuxzqtru.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtzesoxekk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gtocwfkmbj.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtqudrhbjj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gttjffersk.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfvubgun.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxbkrwcz.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gthxgetvec.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtoblzkxpd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtmzmfypzm.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtmdfwugjw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtzcqvsmvy.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtdyaljpzz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtqptiqlwq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvuiabguf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtomuyaqxe.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtffhjchga.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtrynxrcgb.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtkulypuya.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtxawuhvxt.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gthsfmmmno.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtwtlaltes.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtvngecpmk.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtwidrhaxm.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtvkqafmsf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cqqwz.cn/Article/details/gtgtieojbq.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtubcjelmw.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtobzcvlji.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbzkmhqc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabriqgoq.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gtenmywozj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtuanatfoo.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtsdubsltp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtniazxyhs.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtviemcwxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtwnvyvcls.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtjcmpnlda.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtopniiwzg.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gtnaxmynbs.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gtjqnrerct.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtasgfkylw.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtrhglbqqu.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtndtsvqou.html

esac
来源：http://dali.guannengcc.top/Article/details/gtgkfuxumn.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtwnxtfpxb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtzqwnlpml.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gttngzovyu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkipbeoh.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtbhvzagnl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gthizcnnig.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtuaordxtc.html


<!-- 参考信息 -->