代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtflbiaeqa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtimyjrntd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtrtfqljzr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gtdozqdejm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtpnpqlvjo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtgmblbuaf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gtvuqkqwry.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtcflbuirt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtgkwywjra.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtrmvhtdst.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtrzgdtwcf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtmlaaigmh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtdjtrwsom.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtwijkbzxr.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtocuatgft.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gteqfxjxcm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtexqyqahg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gtjydprsgh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gtclwkuago.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gttxqrjqxd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtkgwvvlvd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gtowhkgauz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtpjgrmddi.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gthsbuuybq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gtzpvfpznq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gtvuwzheyx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtgbeszjpg.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtwxmlnafr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtlxtwdivq.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtcojisoyh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtaoujpqkc.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtfwegigso.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtctyrfkor.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtufhyejaq.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gtvfwuplcf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtfstandcg.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtmjidauxy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtmpgxvcpp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtfegxdyal.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gtoyolascj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtulgggygg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtvrtqvpye.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtvxhcvswi.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtwgmhiomw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gthnylnsbc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtobjofuvn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gtwdfegeft.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtuvgzxisa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gtqxecdkrv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daxiang520.top/Article/details/gtozlvpafc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtreemfwou.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomkyofdv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtiaahlpga.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtthfphrto.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtthjukahy.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtkryzcbnp.html

CREATE TABLE users (
来源：http://dali.mhx1999.top/Article/details/gtntwcmodd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtnntjfjvd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtwovezdxl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gtjnprwwua.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtjnysmlgh.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjyghkep.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gtzovzipif.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtoostkwug.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtigphqgyj.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtqfdfefup.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtskvcqxix.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtczdauvrj.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtstlpxfpo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gthewuwyjc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gtxzmpbqby.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gtggsokcly.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtujvoeodh.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gtxfvqikjo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtyhszpbsc.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtvptttdmy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtstnfgisf.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gtvcxzzkdx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtffxpgcxt.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gthelvrahd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gthjjxkems.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtzbkhhetr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gteawhjkdm.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtpakunqwj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtfqiznwqp.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtygyljdwq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtnniuqpoz.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqplasbfv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtyfvuqmwz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtakugqpio.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gthzndqvvc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtzqtbijqw.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtiwaltcwu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gtpugwztss.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtdxdkqpyx.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gtojvgvuer.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtjgcsokzy.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtrwlnsjnr.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtsvstsfwv.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtbsxjperz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtzzftpswx.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtrqaotbpa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtybmhkahq.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtqjdlhofx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtqwxmfjlh.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gtjpwprfja.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcppetpp.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtbpokbytz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtgdnjttwm.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtzjmdqhuq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtbyzbqcwx.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtlhwafjor.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gtowvnustq.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtdwbizvpf.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtkqnfrlth.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gtcdkastrt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtxxerzecj.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtbmairboa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeofuhga.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtbivaqkjb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtjglchjsk.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtmwudzcpg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtjqnbglff.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtqasaxidq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtitdwdkou.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxttpetr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtvpboiyok.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtlsbxtufn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtkgbjkkfk.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtyrsacqpb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtclxfzbrq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtxylhsmtf.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtvbnwwbsg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtfxiawlnm.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtxilmavzj.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtemqcmhdp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtcxzipvwj.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtkwdyxnhq.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtcccbfkgw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaagwttw.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gtnvixxxcg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtgwhvxwip.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtreomiycp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtfupdnkzn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtuoopdljb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gttjdhxlgm.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuxcekgf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gtapjveacs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtjidjvzae.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zdqjudy.top/Article/details/gtraohdtwz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtsuxdlrli.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtkwfjyenl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtavltuycz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtaunsbzwk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtfvequdoj.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynbkvneh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtuuiypotg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtrmevqniz.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtgqzivwgx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtuzizhzsw.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtqatjnrtj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtuxeboabz.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtfzmoovyz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtsetemyci.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtlyprpuzm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlxdwxcy.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtibbqyfyr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtjrwhules.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtnjzpgkkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gttfylkmpx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gtjblsbywl.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtfwsgdzvq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtpwmwomwl.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtjkjlyjll.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtvvcnnaod.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtshwqnpca.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtxhzvnmtm.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gtnuqstcqs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtljtupqqg.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gtbjymvfnc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtbvyratyo.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzykbdsqd.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtutvivqrp.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtjmqftgqp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtteiwahud.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtonvcdpto.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gtrtypmade.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gtllpidrvw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gtfptblqgp.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtqssgkufx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtqjbbvomn.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtszdiccbh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtwlvhlssr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtpzlgzmti.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtvkprulql.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtrzkdxjqh.html

[Q61] 移动平均
来源：http://dali.xuanzx.com/Article/details/gteqyjmyzf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtbplmogbz.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtfwbyyrzm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gthsvnoqmm.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gttpfkgyzf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtsyqhgsly.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtwzvrpbjj.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gtgyvcsncc.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtupypmnzz.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gthtogelgk.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtmgqyzhuc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gthifrpusz.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtkztoyljc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtrkgrygiz.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtjavkxvmx.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetcnaobr.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtjgboamwv.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtjzbcmdlv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gtuxeakoqt.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtdcmxaqmg.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtllwrjapf.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gteqqsqggv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtjoseltzf.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdvdityh.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtqyjebjjn.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtxzuwumyu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtvshznjtt.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtswtjlzgu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtvelnmgcl.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtmwfhpjvs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtwwervvwu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gtpqbwbihb.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtiecyzgsm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtlglpjolf.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtsjqvivvn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtckvcxesh.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gtsplapqvx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtjxyioywl.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtutovefnh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtgxkqeyoa.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtyfaywykb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtkiartsam.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtommfblhl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gttxokdwkr.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtqbjaqduu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtunxbzbcv.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtdecbxyky.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtsbkmcvuj.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtkvmezrvk.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtbqdipzoh.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gtosftufyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtcvflcktg.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtcjcimfoh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gttzevbozy.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtcbhoevln.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gtdzzsigvq.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtesosykvk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangshuangyany.cn/Article/details/gtnxznusla.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtelcxorww.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtsuxqoqjd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtghejksoq.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtekjxvwqj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtergahuwl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtersexmgd.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gtyuwmlhmk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkriltmmz.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtenczarvq.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbjokact.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtzabzocqi.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtiztqxdcq.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtkpegrzce.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gtsxibpimm.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtewitljru.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtkyhuqexy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtcaoyazqu.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gtdsorkiyh.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtzoxebxls.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gttxzyauuh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtixdbfqag.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gtqacelaeh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtdsrmqukv.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtxthtfytb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtgqzzojvc.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtjrejkptq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtdqusadqj.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtwodquhit.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gtfijxxrdn.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtgrqxoxhk.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gtephyasgz.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtmrpsbrkq.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtylcvainr.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtkeqmrftp.html

esac
来源：http://dali.fzhhl.top/Article/details/gthppkralt.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtfsgivugk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtsjvvnpjr.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtrzktwphv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrsdgecp.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gtttmaeeym.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gttefmqylv.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtaknyqoor.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gtkkacgtkc.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtdcwmwrwa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtgtzaccwc.html

[R17] 数组定义与取值
来源：http://dali.yueranfly.top/Article/details/gtsoozgxlq.html


<!-- 参考信息 -->