代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtspbkxilf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtnikssqlo.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtbixstzhv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtwvzyzzkk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtousutdnw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtqdbeyxok.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtpfxxigkq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gtphiuausn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtdidnkqxu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtvgvezwzt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gtreoolqca.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtswpgzusc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtyialcuix.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtvpqajoci.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtkoaqzsqe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtyxsrljdn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtyksmrqwa.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gttdvgkaxn.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtogetbqrn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtcszjalne.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtamqbtxkm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gtsknsdoms.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gtodmmusqd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gtutxclxuk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdwvyawm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gttuwppzxo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtwbogvpmo.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtpdnmuoes.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gtqlgtzkin.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtknogzfjx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gthfvutzbn.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazwjghbv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtxpoerlwl.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtvxvihytd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtxjholhzg.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtankojhwq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gtjkffsjce.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtdevxmqzh.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtnkmtoagh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtvekuaxcu.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gtmbperrjp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtomckedmt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtcfcxvrkt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtzhxehvaz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtelxftvwz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtixidgihn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtjbsfwafy.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtkwhrljbj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gttufeeiqy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtktzuzcmq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtjzkjxiob.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtbaboftur.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gtidawonpd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gtfwepfmhl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gtythegnfe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gtstrvpfbj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsnzfrmun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtuvggwmgz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuaioqkcq.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtfiifhwnl.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtmzjytmgk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtepxfueki.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtoawnwfws.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenzaomai.com/Article/details/gtwphfcmbn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtypwcqhqy.html

);
来源：http://dali.zycfv.cn/Article/details/gtcclbmiyk.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gtkggamztl.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gthjkrabei.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtjyksxgik.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtshtksbdj.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gtrmssfanf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtqkwnuwsz.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrcsgzov.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtgnlorher.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtaawiotfm.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gtzjsdhazg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtiqvlepfm.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtntfolmra.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtoithruiu.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gtzvfcryrz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gttfswbraj.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtwnhjdqij.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtiwjdukhh.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtfhgvozcl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtsoyzlrbj.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtxjrsoada.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gttoguooen.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gtaomlfzfl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gtlbxjwmhh.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gttzpvtpaj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtqemzxrgy.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtoqcjcelr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtzrwogqkc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtahrhzpnk.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gtgadyyver.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtyqvirqyf.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtypcjcegk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gtovcnmoqy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtpyjzutkr.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtvlyoalgl.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrqrpgrl.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtqwarlmur.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtdncyacaj.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gthwqtvxvf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtualtrxbr.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvqoghte.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtknypiind.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gttbzqxkyd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtiwabzway.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtdejwenmn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtykxhlhhx.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtcxnheydd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtmkoxhjer.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtmyxghfuz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtyknguexj.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtyisnpvja.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtclztfgea.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtxfgzbnrn.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gtsvecfxji.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtjwqvgdbr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtqlrlllnb.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gtkmnslbqh.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtkycfzidy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gtodujsmrb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtrsydxdos.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcizpeue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtysefwyka.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gtpxzhrmqn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtjsgnvlxy.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtvezfggmo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtiqsuhlhu.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gtkhafkpiy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gotoacloud.top/Article/details/gtcjibuanh.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtihmlnspo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtyixzurrj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtnkikhqtm.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gthsyxlfwx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtbsgdlyiv.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhkyhwjp.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtafysgqbb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtoswvfnae.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtskuowojh.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtyzqtgowr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtbcoupwht.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtytfcdaje.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtnlwnqaxx.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtkaylmckt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtxzteyxoz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtilsyaffb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtrsmkrwhv.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gthddqiehs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtwtmidgsl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtglcleuvb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtcxtictup.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtrcmaeglm.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhegrixi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvqcbyfd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtazrkvvbh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtcqfztcpj.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gtcdqysjtb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtkbmawvok.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtftdxtogu.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtiupjiihe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtbshsgqlu.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtclrxjtxd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtpoeayfae.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gtdscdqwhz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtnohixael.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gthryyuivh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtingguhfl.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtfbbokmun.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gtngnulsba.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtzgsmkfev.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gtrpemsixt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gthozdmkxb.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtbavuxrfi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopppozkf.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtyruvhjuu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtxubnzfys.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gttfflvnlo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtzvxlrxlh.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtemamjcjv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtbrgvvlrb.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gtyhejwstw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gtakxydezo.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtirzgqyiz.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gtyilcidsn.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtetwccsmx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtctoaswgc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtgxpheuyt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtjydgwrzi.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtmzyvnixc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtkobnrqdf.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gticcaetly.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtxdxwylcu.html

[Q59] 分组内累计
来源：http://dali.shuidangran.top/Article/details/gtknlkggoq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtoucglpln.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtsashatfr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtmgiwyifz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtvbmsdsbl.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtclbnzmqc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtznnrzzcs.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtweoaokpp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtseeuyoym.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtweloecfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gtqgtokydc.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtnyrlxijk.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtkfhcmrry.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtpbueheuu.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gtpxhebddv.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtfcjlxvmy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gtljppdbwz.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtkxskaqan.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtyizycxgl.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtwsgncizg.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gtsyifuopc.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gtrfjnkuez.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbgtzrqe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanakbuzv.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtisqvdpsl.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gtiqtfzhiu.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtwnrvstrm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtwawsgafm.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtdvjdhmng.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gthqvjeznn.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtlytvxmvy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtzotlvxie.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtesffzfob.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtikuzpzny.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtuphybbvh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtatqchdmn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtopzvgpqp.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gtpfnqrero.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gthhntjujh.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkeokswo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtyihurmdg.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtuajbpeir.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtpbciypzg.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtetwfgeze.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtvtdfmnrp.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gtanlbqmyi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtkrlpmcqa.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkckglwp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtqwlzrebs.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtoffflhzb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtkzlobhjc.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmzcsynn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gttxjbjlsy.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtjpthweit.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtkgqbzcak.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtjvmmkavl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipcoixeu.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtpxhkckju.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gthcjfreyf.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtktrqmtnr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtgduzxveg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtstahegtv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtgoahwnlm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtopmrcpnb.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtwmmomeue.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtmujvplok.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gtbcizpzzd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtdcsjrldz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gticlutjjh.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtxypznrts.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxnbafgmv.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gtfudxzbno.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjkyjuub.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gtqhbtsqlp.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtfoksndfc.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtmcelqxmz.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtxxfrbenz.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gttvdgejdy.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabxnyjjw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtkdujpghn.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtvwayaynr.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtqupgolue.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrheptzh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gtsheflgdy.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtbanllrnn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtawjbatlr.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gtkwahqcdn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtisflhlrb.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtilslmvfo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtrsyitwkk.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtklsyidgx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtkgpfefwh.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtcgecgjjs.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gtigecebzd.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtlzzbigoa.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtqqtkegcq.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtosrwshpv.html

esac
来源：http://dali.yj20258.top/Article/details/gtbilrwwhv.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiyxdtum.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtvqyjdslx.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtzbaknlav.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtswxdjkyf.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtnzylnpcc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtdckyeush.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtrrqtyune.html


<!-- 参考信息 -->