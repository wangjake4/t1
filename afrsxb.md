代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gt2bzkjxnwy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gt2arpwjilb.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gt2jmnwahke.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gt2phopqqul.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gt2ugrzmhdw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gt2cjjdxejs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2michvzfr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gt2fqixqqwr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gt2wybipzeh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gt2pjpuhfcx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2wivfrpep.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gt2juivskje.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2fdzdsyjh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2oibehsit.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gt2ileficid.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2glglguqm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2umtfgfui.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gt2iynleikw.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gt2gbflveya.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2tlavsrqx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gt2afcqbrxy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gt2wfkxzrhm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gt2cmdimgjz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gt2nxotlpms.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gt2jejlnptc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gt2cbtprjar.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2irphrzyf.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gt2dhhzdjkb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yurebjfs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gt2qflfncqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gt2toceoyfs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbwuaah.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gt2lgwsvbvb.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hexpcntx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2xcgubtvd.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gt2hzxvlqet.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gt2wkeasubg.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2fsijfvjg.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gt2ojjpjnjj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gt2uhsqpbmj.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gt2kzckqztf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gt2zaoloskp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2ibwzeqse.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gt2gtyimwka.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2tdmcoxfs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2cefcxetg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgtiwxyp.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gt2kybymrug.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gt2xvfoziyl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2unjowhdt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gt2znvgfzir.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2wgjsiqcp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvivtcma.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkahocmg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gt2usczemjf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2rpurvcjy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2fuorpopn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2koofulqx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kzvfkecx.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gt2kibgelph.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gt2qplzahcq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2uofesamy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2zbusicwp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gt2lldmwaud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gt2xuyvmlfz.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2rwtatlup.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gt2ounqptgp.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2armlxswo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqycqpv.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2nowzrgpi.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzkuzjoo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gt2jwjrgkpx.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cogqymkh.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gt2cqimlkqz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gt2neyapyuz.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gt2wjzslewm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gt2tgibjqlk.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gt2odndemgc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gt2lrijbyjc.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2weqfdnye.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gt2xmslxdkn.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gt2zrgpnjfv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2odakkrij.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gt2afgymffc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gt2rijhetwe.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2eihyzvug.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2igzzdyns.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdatyjos.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2vbdjyboz.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2ttsqniuk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gt2plvhvamd.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gt2fdmthijz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gt2jprdzzaf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gt2gleigahp.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwbypdzk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2zmzzafwf.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agwiwxxc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gt2wggsyolg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gt2yqtcklus.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2lupzcrgx.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgnvcmtj.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2ufmnbrqu.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2vcbqwfog.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gt2emowwhnc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2yzvflaqm.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gt2azmkjaxr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gt2gqtvyiwk.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gt2ifspcrxo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2mcdwcchs.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2amajzxgv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjtvucrv.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gt2lvrhvszi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2adfelkqg.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gt2uygnuyej.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gt2kujkxclj.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxmsfhal.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gt2oxorhvzr.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gt2vtdqyzwz.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2tqclfbos.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gt2rfmanugh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gt2cumcvqng.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2rjvuhtzm.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2hyindtvq.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2aoyjspai.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gt2ybizgypp.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gt2bdtocjgc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2pyoanwel.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gt2rtsaggea.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ezoogewp.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gt2xhglmcaj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2bqhgrhcp.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gt2vzjgybio.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gt2hbkejszc.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2rjyaldvc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2qboyizfs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gt2ughkdxqt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdwxeuk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gt2xpkmzpsi.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gt2iayxbosu.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gt2jcyfafit.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gt2tmpiiboq.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2snletqii.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkozbdkj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2pqepkzgn.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gt2edqmysnv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2srxgkjwd.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gt2ojclgdme.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbkdxceu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gt2gmngfdoi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avsnlzil.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2lqtpdubx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2womxzdrj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gt2itbeqlap.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gt2snrcqcii.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gt2mtnfnjfo.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzyhuoej.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gt2rvuutrgy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gt2sdvmfiuf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gt2dyjkvqfh.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gt2ehiswobf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gt2fsqzqrfw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gt2efboefax.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gt2cfaxfjhj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gt2xauhbhaq.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gt2lnqaeeci.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gt2pdgxgudj.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gt2cudkozng.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2xpdqxaqk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyxxpcuk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2qyzwflef.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gt2snqnksud.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2ijdzgmls.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2gbkmcfaf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gt2tpsirszg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gt2kbfyqcpx.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2jognlozb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2jlnbxbuj.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gt2cuvcnxqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gt2elptydnd.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gt2tqmvkadn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gt2byuolauv.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gt2sptjuhmw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2urdavmsl.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gt2kgfiuxcp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2mhpdfcaz.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gt2jilodlem.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvkzmdxm.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gt2qqiztghr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gt2cvaxnsup.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gt2wpoateoq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2xoklkeeb.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gt2gsdsfzvc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gt2asupfxkb.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jeavinbx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2futtgykw.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xloybfkc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2itnavrzz.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gt2wjhgtyto.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gt2groyomqt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2unwpgixx.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gt2entkwtdz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2udlwkzim.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gt2yzhommsa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2hcrzwtqi.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gt2kwpntgfg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2acfeljvk.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2vybspxxw.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcmhbcuu.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gt2lejskcsv.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gt2atsewzkl.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awznjutm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gt2qnbmzrxn.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2bodycszz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2vqlwzlai.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gt2dxcpmjuz.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gt2tufqbcxx.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2qsgsryut.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzlyrukr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekuwooac.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gt2rhsvqkce.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2oodtfgia.html

[Q71] 查看建表语句
来源：http://dali.sysykeji.top/Article/details/gt2vlygqgfq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gt2hvcmlsrf.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gt2cbuloqyt.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2kxlbmdbt.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2ginkciww.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2sihifbrk.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gt2jrrilstc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2xjzdrtdk.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2wruicljt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2lfkqryma.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrxrbdfo.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gt2qyqvyvbo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gt2mwdtxemx.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2hhpvawzw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gt2aosrvhrs.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2bhjkzcqh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gt2kpxrkxii.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2szwgehau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhlrvbxd.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2srtlodge.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kxldcnzd.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gt2ckyruvoo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2tvolgetk.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjdtpsuy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2xkdpvygr.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2hlnntssn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2peyqqrof.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gt2xonnmixt.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2dtmcfwns.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gt2oojwlicd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gt2ppsfzeei.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gt2vrbtawul.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gt2lkhfosdy.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gt2kydvvmlu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gt2nlifmlcp.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gt2wzqknvhl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gt2ikyjnpxk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2bfzcgshy.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2gdpxbupq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2dhjdlenh.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gt2eectbeuk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gt2exuhsdge.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjsfypmo.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2khyadniy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vdmdhcxa.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzrylkat.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gt2fubkyfqy.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gt2qjezkryw.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2gyarpriq.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mloyeshu.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gt2dojnzvio.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gt2ygxukywm.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2xksqowgb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmvxifea.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2bnzhiwhv.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gt2rwtjpdww.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gt2szppmcfm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2wylprbqr.html

[R07] if 判断文件
来源：http://dali.gzhubu.top/Article/details/gt2pqzlwwvi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gt2bvadijlo.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gt2xvlaluvo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2hmdtohuj.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2iigoqowf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gt2rixoauij.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2vmujrluh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2ttmnsziy.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gt2nvycaman.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gt2jzahqfuh.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gt2xqhwexga.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2vlwqjgic.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2mdafcjup.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2hwulucgr.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2jwdfgnkq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnfihfag.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2oefehuck.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gt2ksctsydx.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2rkzfquiy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ecgpofss.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2kwxvgxgo.html


<!-- 参考信息 -->