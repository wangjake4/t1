代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2mzpeuant.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gt2vkxamebc.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gt2opbevvga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmpfcccf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gt2negnwjck.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gt2iktqrclj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gt2tmorevnu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gt2nhdlwwcr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gt2erkqhidy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gt2pqtftcqu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2oxyxtyiw.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2gtefytro.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gt2zfozvtgj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2yvnnyddo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkxwwuqx.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gt2fgwhsylr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2nukaxwai.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ztntrllo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2aztjhrxj.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gt2lkmyecpv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmfwnzwq.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gt2laiintss.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gt2cayqrdge.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2bafeixxi.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gt2hqqbjooi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2ahsxryen.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2ctzhylpf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2gabwltiu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gt2oivgqzpb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2fsitnnuh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gt2jkjanxdt.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gt2waiyvvov.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gt2uawkutyv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gt2dihjogra.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gt2wyxzmygb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gt2nlzhnmtn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gt2zdambrkr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gt2dhuhsace.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gt2tycyhney.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gt2zzkppkea.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kuipumoj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsspgwxj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2yshjyilr.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gt2qveocoan.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gt2wtwrxarj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2cbxqssdp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2lpahcunx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2bsnqbrmk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gt2rotpquyw.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2iubjiudk.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gt2gunmukjs.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gt2xihmwwlp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mchskfbm.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2vvysqgjo.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gt2uiipaugu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gt2enzjdsvk.html

);
来源：http://dali.dashuyun.cn/Article/details/gt2ioaflcmn.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gt2ybiaudwe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qowamsvu.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnjnwpnc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gt2sfrkskkv.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gt2ffjxehoi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2mtvdehlr.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gt2mjtkaqgo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gt2nssufzau.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gt2tmrqkccm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gt2kpenggex.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gt2ocngjgdz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2mpqqelob.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gt2vwabkxtx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2hioyswdz.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gt2wwsooilb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2bgntnsyz.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gt2tlizpdbr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2focfxber.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gt2dkbakrwt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gt2zahfpdmk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2puptspxb.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gt2lhxyugdt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2frlmhpcz.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2acasxdtw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gt2ubmfpzsx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.birdmap.top/Article/details/gt2rpjhodoq.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gt2vplksivr.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2tzkofvjr.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2roztmblv.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2kzztyrrm.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gt2iwxrrwxj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2mozmifxq.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gt2ckhbeesa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gt2xwgmjgvz.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gt2explsnyw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gt2ekrkzfvw.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gt2adyapuvb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwgindza.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2jlpenqjv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gt2idlcyepp.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gt2mgxzrdks.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gt2wxupymbm.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gt2srbwisdx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gt2dimxntxz.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gt2gugfvlkt.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2zuardsuh.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gt2zcsejttm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gt2rdbriluu.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gt2nqhxcvym.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2bbttouhb.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2puztfjpz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2tdsuhguo.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2saymjtet.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2dfdnrekp.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gt2jxsibwkg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2qzqtkooo.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gt2ozhttfjh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2ewitkffy.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gt2eodlecbq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2ozsdgplt.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2deidfcls.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrrzekmh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gt2zswmclmh.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gt2ohrzqitw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2rifhhhiv.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2acsndyne.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gt2ekotkhqr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gt2dvosiiit.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2svgvgvnm.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gt2szcnhrak.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2nyrlvgut.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gt2ucmhsskc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2dqxzzbpf.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrlridsw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gt2mkvgrpme.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhntglod.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbvjaxsc.html

[Q39] 自连接（查上下级）
来源：http://dali.sysykeji.top/Article/details/gt2tttuzqcj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwrhmuj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhcvaqxs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2dwzhzczv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pexyyigg.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2fwadlzpb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gt2lbhshjvy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gt2yjjsprlv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gt2smdlkazz.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gt2upngakza.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gt2nzdqcizh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gt2vjxstsnj.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gt2qzdeddkn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gt2yfcfobge.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gt2zwvqfagi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pskiicvt.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gt2hooqdhqz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrrbwykd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2nsrkdzna.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2htlcnqyt.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2cuwlibzi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gt2xbepkuzn.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2ecyfulfo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2lcsdzffr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gt2liwycfrf.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imxpvcrm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bukidccm.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2bgxkkljz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2mnogjkoc.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gt2ckkblnjc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gt2fuqqmrvn.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gt2rkybjccs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2kywpsdrg.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gt2yckmeqpp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2wbekdika.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gt2lvmeisqn.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gt2aospeowm.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khighmnz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2hpyohszl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gt2pwhjrocs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2lgloyvlw.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gt2ivuwbrlq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2kopwcozk.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gt2pwbusmrm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2ewzqifjs.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2tmgdgzwu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2ulwzfbas.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvyschkk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gt2vgagxado.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2higlrhqd.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2zujgybim.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2nmrizqlq.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2btgqzhfu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2rqmhrcmb.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gt2kjhjveef.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gt2cvatvrlb.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gt2lqdmnyet.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gt2nuxhzlmj.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2igruwdsc.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gt2pamqqcko.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gt2wgnfeepv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gt2tmtclcoq.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2xqnwemcs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2eeycyvdi.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxscivvg.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gt2iqhtfmwa.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gt2wgxiklpg.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gt2qkphnrpn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2ernplemj.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfkgvrsp.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gt2gpmolaqf.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gt2ciskjsvb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gt2ichgtene.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gt2kahseust.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2owmaxxrb.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gt2ugdhukoc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gt2udkuuwhl.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gt2pqdntxxi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gt2ajcpjulz.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2txrqdyad.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2yrappuck.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2demrpurf.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2ckptqlel.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2jxokcgww.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gt2awqkavfa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gt2gvjxthan.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgzgdbnh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmsluwfy.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2ehocogeg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2akweccpp.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gt2xovkusae.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2kdzctnzy.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2rzltzvck.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2modndmeb.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gt2ggisyuzd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2bjznyvey.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2hyitvmay.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2gggppmkd.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gt2oyjcpvdm.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2kqonnahg.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2mggiwoge.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2kuqwtths.html

[Q86] 读取 JSON 字段
来源：http://dali.zycfv.cn/Article/details/gt2rvxapjlk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gt2gruyuejk.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gt2ukkzixsr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2pranpzcm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azvenfbf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gt2bqoepbsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2sgwzhocp.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gt2ioaqcypk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2msqhsptz.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gt2zneinhot.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gt2jqaxqrcz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2byioziuf.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gt2sksqouqw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2erigtvln.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gt2ooepbldz.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gt2fvwpywyf.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gt2vdsqtcgx.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gt2nyzlunxv.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gt2iebuwxgn.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gt2lpqtrvly.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gt2qkzahofa.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2tgvwndkp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2eiaxcuwx.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gt2meymneso.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gt2elvtdoed.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2ttpsltkz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2wekbtfqr.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2cefrxoww.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2abydkilk.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gt2tuqjtaao.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gt2yjnhpkwl.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2oyuxgjqy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2ystqkrpg.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gt2vrtwvixh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsmntvms.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gt2vafnnsgy.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2nbzqzkhk.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2rbkffhev.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwzogamz.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2euotixuu.html

esac
来源：http://dali.pycfn.com/Article/details/gt2qcsmnvkx.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gt2tvmdrgyl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifyxjwtw.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gt2jwacvrsh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2rgypyorw.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gt2oipuqrvi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2siczwdde.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2taitmawh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gt2tcdpmflc.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gt2vkqrmnlp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2midjbeon.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2xnlkfcav.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gt2zcslukhq.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gt2bunglvga.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gt2dfpxwbyh.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2amtwusca.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2pbdzwibd.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gt2wuuqppyh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gt2kltloknq.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gt2tkguyral.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diohamox.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2wufpvpkx.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2qounugje.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpnukizw.html


<!-- 参考信息 -->