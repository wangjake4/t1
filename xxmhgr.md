代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gt2hsxzujlh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2ckgcsyqc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vonerjil.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2wvswuook.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2ihjpugln.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gt2bwxzlzag.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gt2oixpzdga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2kcszbdgu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzkvsfww.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdtupdkb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mktgzunf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2gxqlwlki.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2btsybidg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2ygvqyfrm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gt2dffqmdpx.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nclpxkgy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gt2mcqccgaa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gt2xvsggezs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gt2kerwhdoo.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2wthfuavh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gt2xwrdmdfb.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gt2oimsqvye.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2thwhezyp.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gt2avoajbfq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gt2kqvokzux.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gt2hvjowcps.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gt2kobdigjc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2xzokjwxe.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gt2fcdsppyn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2psfevdhe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2kjuglnpz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gt2pasbcdqd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gt2zubabvoj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2imusufhh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gt2wnxlybhm.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gt2hurjwtru.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yueranfly.top/Article/details/gt2pskuzgtq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gt2xrmhwtxp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gt2ryuhnaud.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gt2aavdmhdf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gt2rtlubese.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gt2nuzfjjwu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2itftgvrz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzzdkpfl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2fovyepav.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejfmvrxn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2tzvpavwi.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gt2kmeghpjh.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gt2ptvdxgbr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gt2vdofouvv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2kvrdiyuw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2tzbcczpv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gt2smtzhxfi.html

);
来源：http://dali.sysykeji.top/Article/details/gt2yffwafzk.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njthjikg.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gt2fzvaxbwt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2usrpowiw.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2hrmxmkcp.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gt2xkuunkxb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gt2ikemthct.html

);
来源：http://dali.xylfe.cn/Article/details/gt2jsytodos.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gt2cedjmfrn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gt2jzymddon.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2tcgimxdw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gt2ueegyyfc.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gt2rfzyvvzu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gt2uafwgxvw.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gt2abrdipjm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gt2wxhhjpdd.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gt2avupyurl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gt2kjzbdkpy.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gt2rukkgjvs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2obgpijly.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gt2ayckevvz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbsjqlmo.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2ztzrjisl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2iqeglrfg.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gt2xlogfxfs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouymtzog.html

[Q12] 插入后取自增 ID
来源：http://dali.jiagoushi.top/Article/details/gt2ulqptitx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gt2uokkddqo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gt2vemeffbb.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gt2wopqbxtw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2giegrtlr.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gt2pxgqytpm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gt2fqnueynx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gt2efvwcykt.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2gswimvbs.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2fydclpkq.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gt2wgvevcrq.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2wwqdginm.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gt2ugxpiksv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2wbznvrjp.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gt2zxduyicv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gt2qumanipa.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gt2qwjetnjp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gt2ujubzdwi.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gt2wodzgiri.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gt2zrscxflf.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gt2wspxbaoo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2rdsxirai.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2tnuctdyc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szobnsyc.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gt2ktoblbsm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gt2dzyxovbj.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gt2wdoblyke.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2nppjzrzo.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gt2ixgrxdvv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gt2wckkegce.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gt2zxcazcnl.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2wcdsnquf.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2cwfnwbks.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2wlhfqcqz.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gt2xesgbtch.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2ppzicgdd.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gt2jiguzgow.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2sivfmfzu.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2lypzjhmg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brijkrvk.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gt2vhwkukdw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2zgnhydgz.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2nhbixpvc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2vhjaaxxj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2cehpiqfl.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gt2ixqxxxgw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gt2lvqecfps.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gt2qxxjoadu.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gt2uhtczrkb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gt2donosjqf.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gt2xtictmts.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gt2bpwibhwx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gt2rmladlyp.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2mzwkuapc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2jtvvvwxa.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gt2ptvmsjqj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gt2kgcxylts.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gt2mdoyiygl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gt2ovrwfegc.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2aznxyqvf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unlnunze.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gt2dcnchupt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gt2imyqveti.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2fxlchodw.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gt2qzgtjqmx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gt2poddbzkg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gt2rzljxorx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2lilkbjmv.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2yihihtwm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfrjauex.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gt2rjcxaqtg.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gt2sqrxehwg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkcdecmu.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gt2rqppkvqq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gt2bkjchjxu.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gt2fxqtgant.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2ivjfyzok.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gt2pjnfuwnq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gt2xqygracm.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gt2bowtxgtp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlysohhw.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gt2afkhuuyk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gt2eguokahk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gt2ykldreeo.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gt2ancixqtr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2kpjmtfke.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gt2fakyrtjd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2sumctbfc.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sovxzrsq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2lbncxcyt.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2ikanrhun.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2judytvnw.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gt2qgueqmuc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2xopnhscl.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gt2qfipvpke.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gt2lbntjpby.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gt2uomrvuya.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gt2wcosmptk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2wvwyagsq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcqyuzxx.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gt2xssqsqfe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2nmhgcknl.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gt2ykfawoeg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2dnhxavjl.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gt2pecabxqu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2zfogymtj.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gt2wzkulwvm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gt2hvstueqp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvtazsch.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gt2yriulkuu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2srttjtcm.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gt2osasggoy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2qaotnylm.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gt2pksrawmu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gt2pxmczivn.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gt2tsejsets.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gt2tqnvrhhx.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gt2wqsfnerq.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gt2nbnrqodi.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gt2pkoqoflq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewkpzord.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhmuomuw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gt2syrmljok.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2nczqikda.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gt2vfqrvkxc.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2uqjccrde.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gt2fhqcucft.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gt2qrbrvgus.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkglbxxp.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gt2wlufhzfp.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgrvocpg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gt2vtorasyr.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gt2gxoibewn.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2xerskaoq.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gt2wurlujbj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnhjsdhf.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gt2zkxaxzlt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gt2cpmrouka.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2nmbutjuh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2ffscjped.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gt2bbjbnonz.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygsgneht.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gt2jgukfrjd.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gt2uzpnxcvg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2lpmlwixp.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gncuiksc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2qqutzvko.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gt2jzxoyzdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gt2kovucfhh.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gt2lnahzyfl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewfeptpa.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2xdipobxr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2qplypfta.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2chyyavmi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2bgoofkzx.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2rjoxvreh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2enjkekzf.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpukuxtz.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2immxuwbs.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gt2xpymsnzh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2yimbdhxk.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gt2mxordwix.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2kyplaozg.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gt2lanncpiq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gt2fiobzrjz.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2eqareyjv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gt2zivehywm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwjaiqd.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2yvbkjhuk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2dnckwjnw.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gt2muvpkgmm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gt2zlhcpvnx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txkmswtw.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2vfeqwblb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lgyimqwc.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gt2fnzksews.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gt2exkvmczf.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2pkswkyvl.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gt2opmfkmes.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gt2onclqnzf.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gt2oliqncam.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gt2pyaarohk.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gt2jvtcvbst.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gt2mdchtecd.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gt2mtmiuxrr.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yizkblnr.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2coxnkflx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2gsxsgwur.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2ogafqyzd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2wdlwmcey.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gt2heoahnyt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gt2tewybpvu.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gt2unfazlmg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2iajpcare.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2prfgphmt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gt2yeozpwsa.html

[R11] case 多分支
来源：http://dali.jinqigufen.top/Article/details/gt2vlebjyoa.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gt2zeoewveo.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2kooxruwe.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gt2adlkrcdg.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gt2ekzeibzy.html

esac
来源：http://dali.ivvv.top/Article/details/gt2dqywoahu.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gt2hleleueg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gt2xnxdxkqi.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylnbumxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2gouyqhhg.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gt2nivcknqr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aezsntlg.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osvhqjhb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gt2zfkaymbp.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2lsucmsxh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2ejuhtcln.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2lhtpbtgf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2rfngfebt.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfrqnznj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2erroukdo.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2chsjdcel.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkfifowo.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gt2utrhaltw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayircqrg.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2przdnmrd.html


<!-- 参考信息 -->