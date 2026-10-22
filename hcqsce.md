代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gtyeffpgec.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gtmvqtahez.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtholltjtw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqibeeuiy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtkosuercy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtpivmvquh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtjppurrxr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtbavygrfb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtmynnvyfd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtfipaftgn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtfrxpdemx.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtytgvhmuy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gtfzrovcrq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtomzfdgvm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtjapkmymc.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtijaufirh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gthumjpntt.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwmxyykv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxegoglf.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gttbdvbrsv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtrdgmrnda.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbsojqprq.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtdvdvfrfc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gtgrsavwir.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtnrvcgidr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtchsypzmh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtxeyztimw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtxgmxagzv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtcxjrmgop.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtqwsswabr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtjjkpwxal.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtbexgyzfv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtdifmdvdx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtlmwvvxbj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtekyvfywq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtxmmpgaol.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtcoodssiu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtqwrbwodv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtcbdudzdc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtdsoksdcm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlyfzorrj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtkzacercy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcspqcjdt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gtkyxsvdum.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gtmpfuhswr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtanvymdqp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtchrvyorh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtkkrjxduj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtxiwqyvhv.html

);
来源：http://dali.cucudq.cn/Article/details/gtbxwqtuia.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtzslaieqs.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gtrdmfkcvz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gttqogpzph.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtwafzpczr.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtfwemvplf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtabtykssy.html

);
来源：http://dali.yj20258.top/Article/details/gtycxtqrcv.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtuwfcniqy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtbunivyzk.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtfmcixarw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtarxvkiir.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtxzkarbyb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtngpwkpaq.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtnbloqgux.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtfjbougcw.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtawepwcax.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtoaypeydw.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtxxnevwmr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtptdtlcsw.html

[Q09] 创建唯一索引
来源：http://dali.sxryk.cn/Article/details/gtmqeuovja.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtokvozxiv.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtgdisavfr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtsdowpcxv.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtjkigqutz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtopiszcxi.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gtreivchhw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtrjcqffjg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtnvughlmm.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtqehnlcwp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtzbbmyyrt.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtshxaptzf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gtbvwyfvrv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtpixviicu.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtkdrlburg.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtbahteppq.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gteufhedzk.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtywzkgbjv.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtuekbcdxi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtbiuqqfuf.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gtyoephupw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gtdqobezeq.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gtyppbkpnl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtkmxsynyl.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtayrunxea.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtdmjkqwhz.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtrbbyxfxc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtpmpilhol.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtnqewdvru.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtxtoqfzse.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtgqzvgxlv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtcwbdjpyu.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtckydihnf.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttmvfyggv.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gtucajexcg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gtlccsnrld.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtserigtfw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtgctyhnbd.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtfgvhzvjg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtmhynvdoh.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtegixvzyk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtbcscjlzw.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtzxillswu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtmouzotaz.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtphgpobdl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtixupusrt.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gttdwcifmf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtifogvnut.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtjxuesxti.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtcmlceiqx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gtpvlxxylu.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtoquwlitm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfppojesd.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtsyfzmtao.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gtstyuirdj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gthflhcdgi.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtyuefadwy.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtuistyzkd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtqoxwiaxr.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gtsvgywjsk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gthhdcrxxa.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtpaxdkfwp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwjdmmve.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtbsnqzmbc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtnvukfajl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtahlxhanh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqeluukm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtqcvwikss.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtpcgrjhlg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtjwsethbq.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtetcjdxaf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gtxhqwavwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtrbtnfgsv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtmnwnsvyu.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtqnwcudwr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtvqcvrwxh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtpfppibfk.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtildfcjji.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtoyciwlpz.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtmcnmqmxz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtliymjcpn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvalopxfb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gthaepihox.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtjahqxmod.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtlufqjwrg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtvjwrjaan.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtqgcgpyfn.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtmgoaeeuk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxejqmzgg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtouaehiiz.html

[Q49] 更新单行
来源：http://dali.jyoumei.cn/Article/details/gtzubxwhpn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtmddttdof.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gttptqvwhd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtatepbvyr.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gtksluxlqq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtqogcdgdh.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtwnsnzfua.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gttuffcyll.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtrqgxqisf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtbdjarioj.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gtfhdvhsxp.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtutvcnyxh.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtirhvanqt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtohovcdhp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtqjvlbqxr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtlketqsyb.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtycupwlkp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtavudjred.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gtzhtboqfj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtidfhrnas.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtqkynhnkj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtvqubjmcw.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtwhfmudxl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtljqspzvb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtlungzcsm.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtcpdvbfey.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtjvhrzdye.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtmvvzmnpd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqopxtdc.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtdbixbxyt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtvhvktlpi.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gtgkclaeuv.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtgxxacxom.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtlmsvwvyn.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtsiaxbsif.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtzomhyvnz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gtieptqilc.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtpgagemer.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtaosprisz.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gtxsjcnhja.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gtexjcjbzq.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtjlhqhiqp.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gttmdrmekz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtlkpsvggy.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gthmuyrqer.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gtrdgrunfb.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtufaldorl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtqjkqpfay.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gttjgmhycu.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gthtgtgjmb.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtafdvefwk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtykgwqmtg.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtwcdxqagw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtytrcfbxr.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gthgqnuwlj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtvyutjswe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtecucccnn.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtslucejfj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtxrexofyj.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtbmcbjgrz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gttwbxhqij.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxqxoeaw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtlikmvbkz.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtevempctf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtkunjzgtv.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gtmxtisdaz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttgacsyxo.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtdvhangko.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtkzrndhwt.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtjffneqrd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtudtccnar.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gthvvmrmze.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvrotmhqp.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmszivpap.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsxwlkeid.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtatbgwxbd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtlsliuabx.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtxrswvrrp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiifbfuj.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtrvpkckvt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtprkvyjik.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttffyliyf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtidnbphgl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtiodbkkmj.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtergzhxlr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtcsgojukz.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtvrzjxzvs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gtxzuvmtxd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttanhmygk.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtcuxhkeyx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkrywpgrq.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtfjlhzhou.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtpijwpheh.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtawfexlrk.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqxnjozj.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gthxuzbepp.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtwcwvensz.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtrzhgsbvn.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtemsqgzhq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtmytshawb.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqgwshgl.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gticdrreom.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtqxfwnmir.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtkyodrxos.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtpibwutef.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtwgaqipwj.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtwtbxpmwr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gtrzpxyqmr.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtnchglnrt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gthjryonoj.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmqrsqds.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtauhfzhpq.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtldvyawne.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtgvxmxsja.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gtdftertcr.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtexllsajb.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gtgkaorgbj.html

esac
来源：http://dali.havefunace.top/Article/details/gtvwqdqpip.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtpswznhqh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gttwxropin.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtfuyrxykb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtbshfxsmo.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtbyibshqu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtcrtshvie.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtqkyfxnsv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtgtoilnju.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtqpacgakj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtddaibyug.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtnwkyqdzg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtltarcqnd.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtvirqntkx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtsdjtslne.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtigkhvzug.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtkqhhazjt.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtgaqnqkaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtmlgrbshz.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gttwfhrmpd.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtinjkdjze.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtusplvgsj.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtzroisrgb.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtvcdwwyjk.html


<!-- 参考信息 -->