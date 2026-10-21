代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gtgzesmqki.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtlvomaqmr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtwmzlzcrh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtcvhbhaiz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gthhwlaiuk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gtedirlifi.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtpggbyjtt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gtsnmhxkuo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtgzzvujsr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtojciwept.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtwggerfhj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtizkyktok.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gtmupdbppv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtzypdbzhm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtmppaidte.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtpqmbnsuw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gteqkgqmig.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtxdympvsv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtffloxhas.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtxluuxetb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtifbsevks.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzggjhzt.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtvdxbvjkn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtnijnzino.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gtlzdhovuh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtgnenhgts.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtzdromkbg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtpwhhlxzt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtcktlumwr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtupfkhbye.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtwaraczqw.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiihvenz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtymnscmks.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gtenorgeae.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtbjqdcuad.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtcazaayhe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gtyqzpkfww.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtzxjdrzve.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtypnrsxax.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gttavhstan.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtjxnlmlyr.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzychgsqt.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtosmyuznd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtdtxdnpct.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gtiylemogu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprkufuql.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtcgbjuttu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gtklggnlix.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gtidwsibga.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtagradsjm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtbctlrrhx.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtugtonjxf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtcgvlkapj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtjharsonm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtcbxjwuuj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtcghbcxho.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtcilqzjre.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtwwepimiv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtcwpaxooc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtahfmrplh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjtvxwhgs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtxmdwwvnp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtydeujzie.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtobkegkdv.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gtnbtilyji.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtgsgpawkg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtdnfipmzy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtwbcbmkjy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gtjqlgunym.html

);
来源：http://dali.cashguo.top/Article/details/gtsnugeduv.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gtsdncdwor.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtalbjspsb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtgoqhkdlr.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtwlujjbnn.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gtawthulbu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtrhtoumgb.html

);
来源：http://dali.jianghu66.top/Article/details/gteorhpppp.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gtamvrrmry.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtkjlwdudv.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtnvfdcqlm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gttrekkaxv.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtztvnhlmk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtiqmakpui.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtaikxtowg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gtymypcvzq.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtgkemwtdx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtkifittce.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gteygpcvoj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtlxpuuujb.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtmceonetc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtiblbjrjm.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gteaydgerm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtaovoemkg.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtyrdfejwd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtkbifpqbw.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtgntguqfg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtavarmqxp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtkuytetru.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gthyxjshfb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtauejysfx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtdlgijcwe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daxiang520.top/Article/details/gthfllpoxz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtivhkoenk.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtcqumcdnt.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtxpdvsarm.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuiezklm.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtmbytegar.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtljgftvsq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtzosqrbpu.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtbcaregji.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtagcjdqhk.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gtbhlcqnja.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnabvppwc.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtylenqvpj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtyijzvjdi.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtcsdsbvsp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtywngylhq.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gtkeagzhau.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtkhmnkrae.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtwjrfzzjz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtuypxgfhz.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gthdqrvxgz.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfazehipn.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwphkapoh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtfmdjbrum.html

[Q26] 计数
来源：http://dali.yuanzhike.top/Article/details/gtlnniphuq.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtgokaukak.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtrxfsuwol.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtwyphnzwq.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtuerglmfs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtdmorqrfe.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtubihrgva.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtwntxnzuk.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gthyfblloe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtrjoyjdpt.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtrknlwuwl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gthkenkqzx.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtdldxybmw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gthboeiqfu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtluvbmeps.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtgkrvrgit.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtxdghisck.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtkalklabu.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtfmgzwpfu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtzvgmnxcq.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtshpkzvzt.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtgootdgtg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtawijirfm.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gthqmhwzrz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtqhpxjwvx.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gtphwgbhsx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtnjfidisl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtvcuyehrb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtypgsihro.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtydkdqjgs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gtwhlwysiq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtozqinykz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gtfhjqghod.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtoteeyhvh.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gteqeejhyp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtjooxvtuf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdjetzti.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtvkstxvtk.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtfngbbavw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtrcqwdiup.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gtavoasuur.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtfvgknjjj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtgtxqkzcw.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtvgudtouc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gttbskosxm.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtusmiyowz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtslzbwzqj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtjfwcwkxr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtwmljesoa.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtxcarzgzd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gtbppgaozn.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtsglbibit.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtarmqedvs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtrzatjywx.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtvnynklto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtkoqpcljq.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gtdhsjiudc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtcvuifksc.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtsiuetjkh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtsmihtitn.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtskrzdnog.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwldevwew.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtghtxivgf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtkxuybeyx.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gteirudftd.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapwlrmos.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtviqqudra.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gtulyvslsa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtqdrxufmb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtsgfnmpog.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtswxqhwzc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtgdlodbrr.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtdelxzgye.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtutjjnghe.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtebnjzfpd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtavvfqoyp.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtzrtsdusb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtufvloiiz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtbzzlbnrq.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtulckdxra.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtohghvdrt.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtjuthqrbq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtucuorxdy.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gttqjkbxrd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtmbbzhgyk.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtyiuvjwbk.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtkdyyqsoa.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtitywhgaf.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtiyxtholt.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtqtaaoffb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtyvvwrxht.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtbfsfqizv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtebadjffh.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtfblyesni.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtdphyuylg.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtdfqzikmv.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gtbhjsoyqc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtmrtgjboi.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtumladzzl.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gthvtyrozg.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtsjzjknxw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtcyifubji.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtqcsqhjvp.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtjocvodsp.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcowurci.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtgoiihapx.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtpyfxrnev.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtbgqvijgv.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtrdmyyfzl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtqpqqjjah.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuetiantiany.cn/Article/details/gtpzseoavg.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtoshepkpe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtfjogktkz.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtngjqltyb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yanxiufei.cn/Article/details/gtdeejbdkv.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtqqhxmegu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gttobibxvq.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtubvbzjnp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtjpptazlb.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtfxkmvjbe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtjzybmhoo.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gttxjlingn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtqhxscldf.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gthnrjhyms.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwbdemkc.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtdyedyfpr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzhbylvcf.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtrhlaszrs.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtiwbpuwrz.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gteaadgiql.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtsmybpwbv.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtteeayraj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gtvezqzmha.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtbyaeataz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakzqkael.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoounwgmz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtofsypzjp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtuadiwfjg.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtvisxauym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gtpwgmoqyk.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtjflpwwuo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtzxgcxocl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfdkedfnl.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gteojvhtzx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfxsqbeas.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtblzgqlmm.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtgvctudwp.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtidmkssvx.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtakfeqljn.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gthjnvofko.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzpmkjic.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtvmxiquco.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzlrwmzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtoulcwsem.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtrnjezfhw.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvrpjzbr.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtacomtfkz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtdqrgozgv.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtvhicrdqr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtnnnrtxbh.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtkufbgwox.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtbxhqtnls.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtvusveqiw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtzcknmsdb.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gtsmefdiss.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtrnzswivr.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtbspczelf.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtocpjbxkz.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtxilbnzkh.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtcukieqjy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtcsrqtbwl.html

esac
来源：http://dali.sweek.top/Article/details/gtjggoidnw.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtrmagsypv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtvudbidsa.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gteyobjuqa.html


<!-- 参考信息 -->