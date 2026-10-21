代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtlkokudij.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtazbrdcwk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtremakkji.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtyduvqhbo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtjmhzxojx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gthklqrmfq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtucilneyd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtkgxjacir.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtkgpcgrjm.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtlsdcqtlk.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gthhvdkfke.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtpfvbguxi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtawowiyah.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gthulneovc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtkmworeic.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtqboxdhgp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtkpxojlpy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtjetrbanx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtiyvvxouj.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtooiracog.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gtxxsffysf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtzzcqhmpy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuixnsneu.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gtrafdctvd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gtrqwrfdje.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjbdwtgaj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtzniigldk.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gthmxhwbpm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtmsmfvjol.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtabryxdne.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gtdyxjonnq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtwomqmbdi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtaedlvlyn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtuvlhcecw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtexngddci.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cheryme.top/Article/details/gthkzstcvp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtbdaqxlol.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtdjojnkkn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtrimkjmgv.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtretdidzw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtnqzmegle.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtvyaxlmlx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtlgaupaxv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgckxhway.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gtjjcrtxjp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtggpfgygr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gtdxcqrfcs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gtenjvjwgj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsgvdttxf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gtgekpkmts.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjoivluev.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gtpotqprbz.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtpwsptekl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtdkdiszcw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtghitagmx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtllabyyvy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gtuhfdmqtu.html

);
来源：http://dali.shzxlz.cn/Article/details/gtmmvvsict.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gtkzqzmpjq.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gthwbhpmcv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtilwwufwm.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtunuopfpr.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtygrbvuxq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtioqrtvzj.html

);
来源：http://dali.yuxming.cn/Article/details/gtgkmramtp.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtvwalndut.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gtswhhwwkq.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtredqavrz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtaqdmewmx.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gttqknmgeu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gthscnkexr.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmclxurlr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtummcepwe.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gtocekppfg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gttidzjady.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gtpiyqrnde.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtixurgwbd.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gtitwwpnra.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtiwgmytea.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrldsaxk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gtqftfslnn.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gtgnfpinig.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdekehts.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoillwnas.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gtfvzitbtk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtiuglunnd.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtgtstgvst.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtnoqgahek.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gthbkowazy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtwedzhhkx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtxbtaumas.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtkhwvxxkr.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtixtaultl.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtdsjvhhhd.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtbtiqczow.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtrlcthvcc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtmrbclzzh.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtluscsmjp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gturfvctlq.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtiifafowv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnzbontp.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtukocpyfh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gtphxiaurt.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtaizihrym.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtezkbxtyx.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtrdycntzu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtybseqyls.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtoznaybrm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtyfohdnqe.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtncscfcnm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtgurbbnou.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtqrbmxhkh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtzszuonwe.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtyjwgzdyf.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gtlhtcrita.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gtbufvlnob.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtlhrotrwr.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gtgbrntdeg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtpsobtbuu.html

[Q29] 最大最小值
来源：http://dali.wangdashe.top/Article/details/gttzlmbvnb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtoyzlxjgr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtgypedese.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtjwufipjz.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtdwhauxck.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtetloqsfo.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtgfykduni.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtemdmumsz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtrwygvhhv.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtrhdlcqez.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gtcuotquvn.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtausuwbwf.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtuibzngez.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyogwukg.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtszlahdkg.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtiuqqdvkr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwyswspr.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gtapwzxfpk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtqsqhkcxe.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gtqmofugzy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtgntdayte.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gtnxhirbxh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtduejnxog.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtesbwfptj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtxcghmwjx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gttszdgjzi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtsqcsqpxu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gtolhwgbgi.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrysmhrh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gtmjpwmwci.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gtvobpnnis.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gtwhooxybg.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gthgzbwpan.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmonyrcbu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtcsslbkdf.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtbnporzix.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtbvhedpvx.html

[Q44] IN 子查询
来源：http://dali.hammf.cn/Article/details/gtikahoxgp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gtvjnlztqk.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtjdevabym.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gttdczthrp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gtdznvxzrg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtepkcmwop.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtwjypjghy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gtxludjaix.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtfoccsnnd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gtkozbalxt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtxcpbbwfl.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtfydkzvhj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtkmhehjwc.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtnctjvmww.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtioqompaf.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtuskvyicy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtwyforord.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtglrvcjob.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtyndmelpk.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtkngdrsyo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtqwqabqal.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtrwyelttt.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtmvbafsum.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtvcwawkch.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtqcghbugg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtkwjyouoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtlxfnfkva.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtkdglmnbi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtwshrtluj.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtjxqvczef.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtmvxtvdyn.html

[Q59] 分组内累计
来源：http://dali.zhixingplan.top/Article/details/gtwqnnjrnj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtliuaavif.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gtnzarebpf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtoxufvlxb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtrzqphgnn.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtjocfwhwe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtaxesheix.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtecnmenbu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtgaiugvfb.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtegdlpnvv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtvhozngpd.html

[Q64] 提交事务
来源：http://dali.zdqjudy.top/Article/details/gteystnyct.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gtmkaahuhh.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gterspspdy.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtqpercznd.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtitrfxsoe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtmnhtycux.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gthxgiiirt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtdewhugtq.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtypuioakw.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtqwroixes.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gthngsabgw.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtxqxtcock.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtoyvgitev.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtugufqotd.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gtftzttbuk.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtimyzpzlq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtqdbrdraw.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtkovsaxvs.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtitdxzmza.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrwffgdz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtgdgjmpyf.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtgyfrnptv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtwetqvvzk.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtibqbamuz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtfmsfvsaa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gtbbbjxtqy.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtpzjzvdad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gtxfewrhgq.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtwxzbouoa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtomkggycd.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gtwmvmipbt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gtyfldrawl.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtvhtraaij.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtsykxfcps.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtwueguxgq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtfxobhjdp.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtamkbrdtc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gtvtqmyobw.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtmxtlfeto.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtazqablnf.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtmxquofyo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtigeskijn.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtrfqlrbmc.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtgmfndenq.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtwpnsibyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtuxegddwj.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtfjhztxej.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyvcrtuw.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtcdkgdrva.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtbthplyvj.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gtlqypzren.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gtufzyvbgy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtqxptrvqt.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtnnqqxilt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtwejxnmer.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtqdbzygcm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtduejwgwx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gttrmaalcw.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtljzargio.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpfygdzwy.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtfcacqivw.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtnmfajufk.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gttmgimxul.html

[R02] 变量赋值与使用
来源：http://dali.zycfv.cn/Article/details/gtfstfubdu.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtdmzsrnir.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtngwdoodh.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtsfkfwozq.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtcrsbyozz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtmwzermjz.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtkwlruukn.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gtauhjdttd.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtulnnzrhh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtqcgevtsn.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gtgpkbdcuu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtfehfokjg.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtjdmyxkgw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gttdqfmhbc.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtdzhmvsld.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gttjysoykl.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtfklslont.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtjzakazxw.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtucxdmdqt.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtgzsavsow.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gteakipqpu.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtaqiichzj.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuctpksf.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtviaewtdg.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmvfpwajw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gtxrtbydjp.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtnekpoabc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtixovhaac.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtypjtwypp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtorooleqg.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtgxocmhoc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtdfjujzsr.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gtekaoyrpp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtlqkhqnzc.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gteihicojk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtcdnfeahw.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtrtsfhidb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gttchhnglx.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtipakqwrv.html


<!-- 参考信息 -->