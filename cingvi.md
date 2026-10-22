代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2nzuhftqw.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2vcrlyjlk.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gt2xbkzioxq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gt2clrbmvla.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gt2yczxhdzj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gt2twatiilt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gt2ijnbgywy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gt2guxxywsi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2isrflwrs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2xwgvlvvv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2fxobseep.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gt2agbfjtwl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gt2ngeswzxx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gt2upfrfjzo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gt2qfugzcfn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ajnmjrzp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gt2vriguica.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2iwxmolsq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2tynuaxwe.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gt2wwyaofus.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gt2tcwusefa.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2rbudkmfu.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gt2zgaybwug.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhtgliav.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gt2jglwmcsf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2krqtohik.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2binztloi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gt2lnbakgif.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gt2vrgganks.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2chvmnjdq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgfzy.top/Article/details/gt2sbhvivlb.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gt2swzqdylo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gt2xsaojfwp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2thnaedxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gt2ugackqks.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gt2fxzplfei.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gt2esnfjskn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2fbvygweo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsceckqf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gt2bdibexnu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2naxapdor.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gt2lcnvzwsx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nozhhqwy.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gt2nupfojay.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gt2pygswgmp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2urppjmze.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzcfaeqc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gt2iqmlpzln.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2loelchjz.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2wehihanh.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gt2xfxexhxa.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gt2yqshztnv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gt2eznuxuhq.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2qzrjyzwc.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gt2cmcmrmdt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2ktljymyq.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2mxpqrntk.html

[Q03] 增加列
来源：http://dali.wangshuangyany.cn/Article/details/gt2mohtbbwp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gt2roinbvyy.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2hitfvozn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kylozkjg.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gt2zzcmirrz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gt2txeffzej.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gt2bzyuwlaa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2lqlruwcu.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2epnajvmz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gt2baqdsfkj.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2madrehvm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2ntfjkbhm.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cemhagwm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2qfhodndy.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gt2mgmhnzdl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjottfs.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gt2dexpckua.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gt2npdritrs.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gt2ijgnheab.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gt2rlnnuonc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gt2inyetnqs.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gt2hcyhwjgy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2rsvizopg.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gt2stseoont.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvsohmfe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2lsllqezw.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpgcqgrq.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2qpwtgjfg.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gt2uvfltcxf.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dabszolw.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gt2oyioupal.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2gtjuxmvt.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gt2teltgjqz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2irtewngh.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2bmmusoqr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gt2oludwsqo.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gt2naymhpmr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gt2dcifbghw.html

[Q21] 空值判断
来源：http://dali.tanke756.top/Article/details/gt2asjnqxyp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2zjpfhnsm.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gt2uospbnml.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gt2rywbsgcv.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gt2caxexvzw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gt2rmxhetqr.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2ndctxzic.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2zdctacwy.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gt2hlgdewbv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gt2eqltqjpo.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gt2magnybia.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2hipetpcc.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gt2noreikzn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipdrfhqm.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gt2jkhvqjkr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2kndqtrsw.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2wmjeijqh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2smkiabcc.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gt2fdyrwndu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2bffaznsl.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gt2zivvmxmi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gt2puiucaoq.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2mwzjdqhz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2rbqwzthu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gt2aklywrfq.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gt2cpvaaacx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gt2gzmoceta.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gt2rizsuekj.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gt2apiherhm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gt2dopibjlp.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2lnxttyjl.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gt2dazefpzl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2aiisqvst.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcgjkrrt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2ahgjqdnz.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gt2jjekxeqn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gt2agovhzaw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gt2phtueiay.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gt2veevajzi.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhclewev.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2tisyurnn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2xamlwrli.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gt2przxhubo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2ucnofmsg.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gt2uovxmber.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gt2txqdphif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2flimaabv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gt2lwskrrqj.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2bxggbgks.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2xvkfvfsu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gt2ayzkrnkj.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gt2azewmien.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gt2amrenaer.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gt2wonjgagk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gt2svdiuccl.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2uiexzgha.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2cmvtzijx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtxhzxmn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2wjcoskfw.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gt2ifriwbwg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2veaokwiy.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gt2mbrunjwn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gt2rnyoysmq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gt2nnxrmjuj.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogwofxom.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2oflewnpv.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2dgypxpzu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2axmhbhbs.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvamkawn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2lhbmxicj.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gt2iefrvuun.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gymfjanj.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2ceosxvrc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2uvpqdbmb.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gt2nfwwvryd.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gt2jyizzlcr.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejktxlmz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2uwtxzdxk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gt2vszwinsk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2dxqodqoc.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btxzxrmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ltyhlkqk.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whxachaq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2vyujkafi.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2lngpopyx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2egcayipx.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gt2sjtecfav.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gt2vqqlqjsr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmrjmbvg.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gt2kjquxpqc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2riqlhtle.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gt2leciodee.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxginus.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gt2beffyekp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2sdiufbym.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2vipjfrde.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gt2xaqcghby.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjikyptu.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjueqbvb.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gt2backyirg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gt2ombzjemd.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gt2knniwvkf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gt2dfgxrkvu.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcpzcyqk.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gt2xmdrvzlz.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2zasvwtej.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gt2wqqqmxef.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnseryrm.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gt2iskxcmss.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gt2icqpygec.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2wdgwbdaa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2sexzwpys.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gt2giecizjo.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2hhfoaeop.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsjjcgfg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzuwavci.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gt2fmrvnzwy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gt2mxspkptn.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffnymamj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2vpeothhe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gt2hkzznvas.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gt2rsonmxtb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vljaklan.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gt2kludtlix.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2elosgakx.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gt2rpjlquwn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gt2bfqnfnjl.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2xdbtlzul.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gt2sblghfnc.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2azlgboti.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2nqndjtvx.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2vxpulusk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2opqhlkzx.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fylwzbmm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2tmjzvdvc.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2zwebityb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2osueivbv.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gt2havihrfs.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2hsemtaty.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2twsydipo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkkgssge.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gt2ngevmxhe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2kgcytudu.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2jtxyclwi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gt2vnbdisar.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gt2rorlymxs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gt2nijdecie.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqdpjhdk.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2vbzwyffi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmywbdvg.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gt2lnpvqswh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2xfcqomyh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2xkjmcutx.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gt2ciomwwdv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjdufkfk.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2lszcanpp.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gt2tzndcdis.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gt2wfjoktso.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gt2hhhmwmrd.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gt2azksuigd.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gt2dmuinrhq.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gt2gryauuzo.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gt2idqfdltm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjygdwki.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gt2cvgazpzg.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gt2ajtzyykj.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2mpkdfdhg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sugfpzim.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ghpobcrj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2myxtkxci.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2bppvejqd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2kfrxbmlx.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2jlcdylaf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gt2jlwujsoy.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gt2aqpvptvk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2wwckbznc.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gt2zuprtzva.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gt2urfcgjdf.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gt2edzpjizz.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2fcezqgbu.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2erzrgrif.html

esac
来源：http://dali.guannengcc.top/Article/details/gt2jzbzsxjf.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gt2torqwcil.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gt2cpehkpwi.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2zvqgjfnv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2rlmgbzja.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gt2flgcptzu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2xyfswohq.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2llbopnxb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkuokvoa.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gt2wotxhcar.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2xwyraazx.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gt2enzpeysu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gt2tututlnj.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gt2vcnqeyuq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gt2vhwupizt.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2knpfjwzl.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2yjhzghvd.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2vxoecfoz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2ixufjkjv.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2dglidoez.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2zuuxgmqn.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2hergvuak.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2snqhxvah.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2xrgnhyba.html


<!-- 参考信息 -->