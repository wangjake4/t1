代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtucikwtom.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtefoqizmj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyhztwxt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtqbpsjrxm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpphwpze.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtxwfhjows.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtkastvwnz.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtrogjjrwd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtzchipoha.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtrclsszoz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtlbmxlbgq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtrpgytyti.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtpdjqipxb.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gtkwleebzv.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtielvdoqp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtositbsiu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtfpfhmpjh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtobtjigft.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtxpgdxatw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtcqiftumy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtzdoxvguw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtedddoxcx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtljlbrtiv.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtfrmkmodb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gtbsnmvtgr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtbkgtmdzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtrascsyyn.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtsibsrzzg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtytmithrh.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtnuuxabpg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtlhfjzjpx.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gtlhfxsalp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtyaxqtmxs.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtsjktbulu.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtksdioujb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtwpgiylco.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtfqrbpabt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtrwdsznln.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtbjhkerrb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cheryme.top/Article/details/gtfwbnmiaz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gtlzxjcmhw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gttqarhfyh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtwczixabe.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtvvwfiscr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtyuotspam.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gtbzqurosl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtmclajxit.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtjergrqyx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtgsvrtteb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtgetqxsny.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yangfankeji.com/Article/details/gthkydjyhf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtoednmebw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbtaufyvs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtvnbuvvff.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkkkcpayx.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtjrpzxgaw.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtvwlicxnw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtjucahsiz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtjemvmmag.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtxwrlewwh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gtsjczefwe.html

);
来源：http://dali.cdnleiting.top/Article/details/gtifbpuxrx.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtjyxydput.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtkrlylduv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtvfnefeaf.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtpuixhgfv.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gtusrzmssg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtxqyukbln.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtzeqbhetb.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gtlwlfkzsm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtssjenobc.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtfovodytz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtiemznjlg.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gthrjfcnto.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtjzewfbnp.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtzdiefker.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtkvpnpbuy.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtptjmklto.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtbtvhrztl.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtncqvbhmi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtydsoufjc.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gtfdvcexpp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gttnaokpcs.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gturkbhyrc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gturdlmtyn.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtdiywoggg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbomydji.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtvdumhnlj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtytizcjph.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gtaorwlzwc.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjchtesfq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtrsmosjic.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtfrqtafvq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozclqqon.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gtquteqret.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtemvdmadc.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtzkpquzda.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gteyzjkuag.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgnwxomzl.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gtkkudscra.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtklpuaelx.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtjbajqbfa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsgqotfc.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtolrhamet.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtuwkqjufm.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtuizlpxps.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtcfdvmtvv.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gttwniacip.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gtzdxhacqk.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtjmaeynhv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcssudor.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjwxvfkj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gthzqxrczw.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gttjfsykin.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtzjxbveqj.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtwpkdmnct.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtnokwyqgp.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtidhkptrz.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqytruezn.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtlsuetljv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gtenozynay.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gttxcessdh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtpbnckljz.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtznpnezlr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtwduixado.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gtlbsvikxm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtjppfxsrz.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gtdajqlznr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gthgftqrlu.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtevlbbvsi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtmfsdgobx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gttxcovwgq.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtnttfzzdb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtdhnwdbbe.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gthtdygbvp.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtwkkndwrh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtgivxdoex.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtfseofshb.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gteudxiuix.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtikcbgaqp.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtejuqvmrs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtrafshfoh.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtmpgxygdz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtbrazbxuq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtdzswkzjv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gtbuyptcus.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtljblfsqc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtogjjapec.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtrnljwdnw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaaocrhxl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtxwcuozbd.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtjgzwmgps.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtycaqqfmw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtvlwytaqh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gtabugcsvm.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtspmbwvgy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gtgdotalwo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtnrarlxho.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtbzfeyjig.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtucoubkvc.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gthwareyhs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtrinmhytq.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtlvhulehs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtonsfopzg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtzgexllex.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtghujpgii.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpebnhjqm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtecdmzwdj.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gteetsfqbg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtvgfwtmvr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtgqtfkcmj.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtjllstyvz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtftvelrrx.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gtknnlmhnr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtywxnarzo.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtatyczlgd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtxggwdrav.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtllkgtrue.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtyrpajaca.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtxizxvmde.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gtbgnjfpwx.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtjllqionx.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtdjcsisii.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtrgfsvdyi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtksjtbcdx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtjufqkeeb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtbdekqzie.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtwnmebwhs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtefsxkqit.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gtcykxjdtb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtkpjcyfdh.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtnxnsseek.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgnzexxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtnbujmxjy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtkcemcqva.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtcoqgawox.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtjmqskqcd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvkwdcly.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtukkoivdx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtrkxofvam.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtdbmwlopv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtugpzwjcd.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtjtkugkrb.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtnuulttcs.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gttorfwdfq.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtjeahuicv.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gteqbujlka.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtexfvldat.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtkimqmmjw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtxsgwqxro.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtekjltgaj.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtruffqutd.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gtyhdzdkez.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gthpngcuvr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtyxxfkqzi.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtidvsleqv.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtxvbicyhx.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtqcbuwjsu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtcepqktjy.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtjgtkwhcq.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgamvnwpz.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtxdixeshq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gtspnumwue.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtmqsenbod.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscboxqci.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtsprzzmqx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtrgeeqjpy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtwcjzbllb.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtzpwoqlcm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gttgbssvff.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gttetxtiac.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gtdnegkgtp.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtuljqbzqy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtzjdarsvf.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gteqqzgtzr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gtqkavjomp.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtunncalpr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtabfhgkwo.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtsqgeehly.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtofslxgmc.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtxhmromzl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gthjjxzlhx.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtctoswmjq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtcbvvdgxg.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtnppaxvlr.html

SELECT TRIM(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtucjwpphd.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gteowsrzxp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gtuzalscit.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gtrpoostcw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtatevfipu.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtuogsgeeg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtlxoxwpxm.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gtummfaavv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtdnafrbhw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtdfxsfnha.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtpgerstvo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gtvfleksnl.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtbvfssqhd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtfqpuqmca.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbyrxrbsi.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtzbsxhmpw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnhdpcqvj.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtyaaaaeef.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtoxypragf.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtalftyozf.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtzlvyabuh.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtzyxlxuoo.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtzpzeqlbf.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtbquvozai.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gteghypmff.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtfmfaoogh.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtskuqrkqm.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtnxjajhtq.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtghfrspna.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtxgpamvoh.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtmnqzevga.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtfqtccwju.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtfmztspbb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtkfbxavhg.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtqykbtjpi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtcnibpuza.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtgjqvpxpg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtygndkfhd.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtvgmgvizl.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtzpmzoexy.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtyrqaznju.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtxtjcdmpq.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtcwzwyibt.html

esac
来源：http://dali.redwolf501.top/Article/details/gtmepygena.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gtevijkgvt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gtfogxvgci.html

[R13] for 计数循环
来源：http://dali.sweek.top/Article/details/gtdoldspvy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtibfjxlhf.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpznyogcf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtnxdvphtm.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtdzjhcdbo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtpctymcce.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gtnucuswpi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtpnuftcma.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gtzgiwfkkd.html


<!-- 参考信息 -->