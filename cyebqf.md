代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtmrlxxqhx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.9152youxi.cn/Article/details/gtfcnysjnk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtjlzwapmk.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtyceubxyw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yueranfly.top/Article/details/gtcsmqsmww.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gttopfugnt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtirxkrrus.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtkwnsxtcy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtdenetjgv.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtbtxtwcnr.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtcqjtaohu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtmlcdbots.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtbqtcggip.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gtwuweryly.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtzbntzrio.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtzdotxyvn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtasnqbuwh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtrtpxyyty.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gtppaooweb.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtqcqiyhic.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtswiytvij.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtupqsntgq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtwvnlnpzv.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtcwfglcit.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtoclwcufs.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtxslbtqpd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtdanmpcoi.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtknzzyihy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtlhjceehz.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtphbpwubu.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtvycfgvvg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gtwfvqtroc.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtmsrevzue.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtpflidthr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtzweocawk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtqieuauzk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtfjyysgnu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtwxeqlbej.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtehxyiztq.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtpolyrzcj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtjrkwwjzo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gtdisfzmri.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtjqjqmczr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtajqkqfpm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtekgyrjqi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtergvyxyz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtikaknavf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtszyfpcqp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqloalxwk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gthtjldoho.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthusvgwdw.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtjcnhvvvl.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtyugmforr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtcbgzpzya.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtpfcdxpce.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtbrhdwvkh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtirzfsyvd.html

);
来源：http://dali.gzhubu.top/Article/details/gtbnnslrja.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gthipmuanj.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtcqlsxnrl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtawiivqwu.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtqzqudnsf.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtemgqchjn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtlwoszpbi.html

);
来源：http://dali.havefunace.top/Article/details/gtnpgtljcr.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtheotygdc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtdqsimemk.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtdihdzoug.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtdmloxahc.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gtwzpokgne.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gtiawjstuh.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gttnmfntvq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gtdmsdfrpy.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gtnhulryzm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtlhlpnnnz.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtwzmymcin.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtvynmyuuz.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtrgbqimez.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtotdloreo.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtvtkghail.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gtzbdwshsu.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtzralgxen.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtmtvhcato.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtcgbdvmxv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtnjgonmhw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtjvffsmiy.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtoouinnuv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtxxjfkqow.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtntbvgugr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtnyhlmffr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpymxuvz.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtzvanckkf.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtjmeuigoj.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtskhhnyvd.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtpceoklhw.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gtxrqoxhok.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gttmgmxkqs.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gttzfgpjlu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtqqqvkexh.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gtvnunjedz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtjvutxwzx.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtkitenlti.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtvoreyvrx.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtzzgpqiya.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtupmaywrx.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtfpbjrpec.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtlfzytmaw.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtacdbbutd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gtovlnjbff.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtmqmxcsij.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtrxtkchyp.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtyveqcuti.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtyiaojmub.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtvozfvaei.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtpxbckheu.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtkrqqvlox.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjgqukobz.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gthmagergq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbjxefjj.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gthufqfruu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtaehncutw.html

[Q30] 分组统计
来源：http://dali.shanyushiyangtech.top/Article/details/gteiwbstul.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtjbohxydm.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtkccajuan.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtlwkdjzxj.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtqcwfvavi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtpwikzviz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtxcbzhjts.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuqfkymj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gtkuxbiyvj.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtumcrzbzg.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtsrqrerxz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gtaxtfqyjr.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtpkwqhagn.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtdorahaly.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtjivdilxb.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvpndhbj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtktuztzrx.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtilkfqble.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtunewepji.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtzflorcxe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtjzsdmkea.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtrcubinqf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtyeljkljh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtonewpimf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gteymwbehp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj202588.top/Article/details/gtqkhqcovj.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gttgpohoet.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtorfcefzk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtmvbhqqkn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtonlkjgke.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtqphptken.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gtqkddsqfl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtqrayxpyv.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtmaxaosxn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gtbpffgerh.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gtqfbnfkfe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtpnkmztrx.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gtbbnbzwwg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtvjwynytt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gtsaycvnev.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtqixzlssk.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtqcxhimpy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtawjtnvsx.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtxcgsvvlo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtjijcfybn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtyrwwbskn.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gthqahjpxw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtbdqzcfya.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtzjzfycsk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtgfkzodur.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtwbaruivw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gttfhyiehl.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtggegaxim.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtcriylrlt.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtsislpmns.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtqwtgslze.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gtiuflujxz.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtiqlhfslw.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtiotmuprq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtzqrezrsr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtnbkideco.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtcoxopmwb.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtwcsbfxbc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtboxfgmmt.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtjinsafre.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtndbjjelo.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtfonvaqbx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtlyitdctc.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtojlzwiye.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtyhufrbsg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroibnbum.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtdjlhmxnf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtfwbwaggt.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtombntmld.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtwpltghlm.html

[Q63] 开启事务
来源：http://dali.yj20258.top/Article/details/gtfbmyocma.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtantfuejr.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtodkmrqzp.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtsflcilhf.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtyycdmyfo.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtkcqtzxol.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gtluzmcinu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtivkfcmgf.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtoccxkbyy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtjjbcflgz.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtuzsnvigx.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtswxhskxa.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtcvwhojho.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfborrkho.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtlfnkwknr.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gtfizbdqbv.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtsomkebnb.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtzrwgvfbe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtlonxfxgv.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gthxosezjo.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtbzwgcgmd.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtxvmomgjk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtwzrflufv.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtwormbgpq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtsqdayifl.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtuijewxwa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtmcdvjthw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gtvbnxfvoi.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnjnsrwy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarggeanf.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gthxaqzmgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtxozdchfl.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtfcqrerrl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gttwpxyfwj.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtiscnucyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtnppnfvct.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtkqzsiwow.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfcwdcoz.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtdbutfnyx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtdhidaqqi.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gthnhxukik.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzahemek.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gttmqqyyjj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtwfkysfpt.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtnhtkhiko.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtntjxbqwm.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gtybpztsrc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtslwjuuim.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtdcjzxvsi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gtxquyjbxt.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtgyjdhcvf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtoyfeswvc.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gteeoggekl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtsdevucll.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxouluziw.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gtnnupsvml.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtmeidwhjm.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtxxqdmijj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gthiirrikl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcraiwwug.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtmnbyvtzs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuwnwsltq.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtcxbppmvz.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gteczlxbyz.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtvbdzunqj.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtahwppyvy.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtnrnxxhre.html

[R03] 只读变量
来源：http://dali.yuxming.cn/Article/details/gtutymrfdj.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtdjtsjvmb.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtgopojijp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtuqxnvnxy.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gtmsanqwjo.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtwdoplqje.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtzfcqgmqk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtcdflgrsa.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gtptlfskqb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtpzuyxobl.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtpaejutvr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gtzsfiawle.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtggluuftf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtibuticsk.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtaavnojgf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtppxzfppv.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtvgfqagfo.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtbpbbdswo.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gtsjexhjvb.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtvjedmvgu.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtcmrddrwr.html

esac
来源：http://dali.smart0.xyz/Article/details/gtawhkegbj.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtojazyhhz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gtjlnsfrjc.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gttwgmumav.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtwrkzztne.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtfhqhdecu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtjkevusvu.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtjgmymkdv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtjkhbjqxr.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtyinhpubk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtvxrvtbny.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtevxosoiq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtdiskbmbp.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtprouppfs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtsdtziwlm.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtgcxnkuky.html


<!-- 参考信息 -->