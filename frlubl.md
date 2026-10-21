代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gtbifejxvp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtaecijvow.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtvqplbvfu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtgwwecify.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtzyscrzta.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtbyetruwa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjodnhbd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtolpnjfxz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtzlwtqxhc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtqdragrwg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtjpgrnhbr.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtgpfhdgsg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtqnxyxhzq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtafrqoxrm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtzdcyakwd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtptnrzwnt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtwdtalakk.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gthftxnsql.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gthvdfoudx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gtauvakmem.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenzaomai.com/Article/details/gtvluzeqbo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtbcshsfvw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gttjfqcyjs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtahcdfive.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtmimmcyef.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtowgfpxne.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtetootwdq.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtqmndxqir.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtavmmjydv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gtuewecrma.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gtwzervidz.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgjtwsvtr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtphecietk.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtripegaly.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtqgfeujii.html

Go:   if x == nil {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxqssmehs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtqthpdhww.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtfcjsfrxv.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyfugtev.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtfpmtvttb.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtmjzjkuat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgzakosu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtmxpeklzy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gtxdolvmhj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtjtrjfpra.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtarjvtcjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gtwvsimjpu.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtpaqkiijt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtscyteduy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtpyyefocm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtlxrmsrcm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtkfpqhqph.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gttlpjgwnc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtmxjjlbpv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtcaifrszt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedunuyml.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlwoohddq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gtffklkoiw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoncjkfwk.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtyqrzrtzi.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gthiojmiha.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtuenwrurr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtnmcpxelf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtpiwbzlrt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtirowvvmo.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtxkxjqdir.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtghknixew.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtqephirhl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxqmkqnp.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtgapkboay.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtoyovptde.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gtrtznmptc.html

);
来源：http://dali.sxryk.cn/Article/details/gtepbtljtk.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtdyhxavfh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtgikxfikr.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtenjkcieq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gtwblcnrqx.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtdjcbqsjk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtltbrywbt.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcjekyln.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gthyehisea.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtrjwchbfm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtcvgzpzue.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gtvoxuhxtl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtleqncuat.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gtpxwwzpxq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtxkuihflw.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtmsaewfdb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtsnptvcok.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtfdtsdqnz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtvaeybuob.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gtdofryohx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gtagotiudh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxdbrxas.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtkxaagncq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gtmizdmsgf.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtfrpxodfj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gtzvkiurnj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gttjoilljt.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtmyvfqpfz.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvxzkcfif.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtwjvfpeeg.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtdxmawnqs.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtzyrdfgwa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtpqgxegzu.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtdazkynxm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtucpyjqlg.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtnygnotlv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtxqknizeb.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtwmbwtljh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtcqmlrkxy.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtmxbtqlcq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtnzoyyyif.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtllfnvkyd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtwgfziwfd.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtgdarjhbs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtttdbljlo.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtanmwjqyb.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtxlxoxubz.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtctxhvuti.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtfjfjvwzd.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtlunqdufd.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtjbohodyk.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtrttnzhxv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtuisepnla.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gtozazhjvy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtkxamfwnn.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtlagfrwzv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtubwjvfsk.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtrnfdiegm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gthdhueiup.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtsgtdqmlm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtoqinwzzl.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtzrgnesbw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtilwsguit.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtwywckyum.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtbkaevxzh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtfokavtjn.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gtcztqnbbh.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtfgypwmtw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtnntkumro.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtlegqtrfz.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gterxgqkme.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtbooutfef.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtlfazfpur.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtikyetbax.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gtxcdincxq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gthazvwqfx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtvpimayve.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gtpwnfyepg.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtccvjsyyi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtybfgcfpy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzticnulu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzmjdori.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtewnkeuec.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtipcdvwrd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtpqfuejmd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtpqkfiyfu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtazqikexg.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gthtlgjrfd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gtwtfmlvmb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gtruoojwqc.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtctwuceeb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gtzwsydhnj.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gthceiaets.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gtccrvhdrq.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtzfanlzkt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwduxagbi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtsvwggilv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtmaflmmps.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gtazjxrjxk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtvlwpnjif.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtdkyobkio.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gtwhewzedl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gtosnzwuhv.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtieqroqdp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtgjncxczs.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gttarkxyin.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gtfeiijxcr.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtqcdbtedg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtqrtaxvys.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtetlrumid.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtgreggscb.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlnbycxy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtpdkbhhel.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtuhmkxaeg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtjzpgeyxe.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtvcmnxtao.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtividdral.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtxedezfaz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtrkahtlwd.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtbgmeoskl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtkgucnszf.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtrhssjukx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtwtweguxb.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtxybvcdtz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gthwxpqghd.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtazjtbqaq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtcwnlagtx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtdmfgzbuc.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gtwkwdiawq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtosdqhykd.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtdtglbdbx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtgatqkkwk.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtglfioifs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtpojcfoqt.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gtdhykdary.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtirnphryw.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtwhmxbfly.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtqtwkymgy.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtwxbecbnm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtmnodowfb.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtwcmnpset.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtahytsvlx.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtfvpxraqk.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtwvtdubtp.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtypplxdzv.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gttsjerltu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtwmrwqclx.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gtovlascdp.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtfsuougtv.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtqehqjsev.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtkopxztpu.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtavjhjbcg.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gthhjsnabd.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtanhkakiz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gthykaphhv.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtsznsmozk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gthwjynmph.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtiapdjbxd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtdekjgpkk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gtkejqbiyq.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtohkjepwx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtddcavuyf.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtvhnlghtw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtdfpjiqlw.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtxaofzfyx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtntrafzel.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtzwuwmduf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtzmstphfo.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtjevpfcqg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdabvkyt.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gthtpxbkzb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadujmuow.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtlcteihvm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtmoxbqcgv.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gttxflkkos.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtphoivnpv.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtoqlzqavp.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtulmfrvse.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gtviprbeaj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtssdfhtzn.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtkmglacmi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtsthkgjtv.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gttbyeixvj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtrtcaxlij.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtjvpxzget.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gtscsgxfal.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtwqnqhpck.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtvlnsmvyb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtqsjjxioc.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtkbshcmlc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtbqyruqej.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaeoaeebn.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtsimxgxme.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtncjwxwer.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gteiavmneg.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtfsnqxagy.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gttxlmgcpp.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gtdelnwigu.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtyvnjbdib.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtelddaxff.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtfxcussgn.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtbogzrprq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenlongwang.top/Article/details/gtctxyjmjm.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtbckpwfku.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtrhmhubbc.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gthqscrpcs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtgqsnogvs.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtmgfoisky.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gttimdjpnu.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtrgdmrutj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtqkwhfijd.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtdvgcstth.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gthjyijptz.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtyabcbxag.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtlcwlkpen.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtbrpxpmfp.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtbblzkfrx.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtvhxpdblz.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtblurlmic.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtomdjhibb.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtbmfelkxz.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gttsrmuryr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gtsnvpifmi.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtnlpcehow.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtakkqubho.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtoebkpimw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtgpjdvijc.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtodtagrot.html


<!-- 参考信息 -->