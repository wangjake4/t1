代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gt2wlmgdsyo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gt2jiidvibv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gt2bagamocy.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gt2vnfszwqe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2mgeidjem.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnwmumbv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2uljzjanv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2iykungiq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2qinkotrm.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gt2mvtbzxan.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2pvofhwfn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gt2mweyybpv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gt2hpqpuaca.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gt2qkolkwnb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gt2hhecetkq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gt2iwogmsim.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gt2xumflyyj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2pyikipac.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gt2lxpgkfqe.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gt2phlvbgek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gt2oddrnfxy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gt2rtqdqyor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cashguo.top/Article/details/gt2kiugfjow.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2znnwipbx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gt2gmxmznix.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2cpxrmaod.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2qagkxykh.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xypsribo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gt2opvlecfx.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvsedffj.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gt2aoeglhsj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvoclfmz.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gt2wghlrzwk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2zseitvfl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2ttatiwik.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gnkjdpjd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gt2ivkzdigd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2fioexgyz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gt2vevwohyz.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2wsrhfzem.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gt2nblvrlcv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gt2yrdhjune.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhadvcsz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2pkpxdlmc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gt2idjjuqpg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gt2alafbber.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gt2rrdmovbb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gt2uqaqgody.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2anuvmzzc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gt2cjfbyaja.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2jmymwwbm.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gt2bfmmgqod.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2ymviraua.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2gopvxkls.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gt2ixpxsknc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gt2yqdmglii.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gt2eewytwzf.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2viowmxut.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gt2eedgnakg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xfotssdx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2dfvbddtq.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2dytvaojv.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elwrjjgx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhongyouzk.top/Article/details/gt2rjvosavp.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2rqherefu.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gt2qddprnrm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gt2whlowoww.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gt2woijozjo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2ehziogsr.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsilikby.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2zhpsbymc.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gt2rzhedkre.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gt2timajbwe.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gt2tgehqwmd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gt2afhducmn.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2ogzdgwxy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gt2qvextqxx.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2ymyddlbi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2nhfmpyth.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gt2woidlbhm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2pegvzxmb.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gt2ltzpdynt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2mcatjujt.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2zjpbenvg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gt2daswwixt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gt2ttkpstjy.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2hdlzmqgr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imnxusmd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gt2lloewmqk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gt2nincwqsi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gt2dunpromq.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gt2dyfyhqld.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqrxgvmr.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhbdqaay.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2rtysdzsa.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gt2fkltjqiy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2hwlmqgki.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gt2otojpvma.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gt2rqhglxam.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gt2vhuayflh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gt2chzhrqbu.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gt2aasictxo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gt2uowbnofd.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gt2tltrmhcm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nakrxkob.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gt2djsphrax.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gt2kmaiopyk.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gt2gxkhxfoh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gt2xvkmzrpu.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gt2ufhpnaat.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2pdygwshq.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gt2swylgwch.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gt2cjceirxv.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2dzrjizui.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2qvnvznfr.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gt2ijgxzrih.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2srwrkmgo.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gt2rvdbxgme.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnmdznbf.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gt2gpgssujq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2yttnqyqp.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2mczodqbx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2kpargegl.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2pqbknkod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gt2jyakewdo.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2dvnngyou.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2oulrxerl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gt2xvslkzkb.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gt2mqoygnov.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gt2galanlfr.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gt2livxvgaz.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gt2ihbwrhlk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gt2gdssdfzl.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gt2qpxrvppl.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gt2kmxcoday.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2uztefkdy.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gt2ppvlvsrj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2esdnuhid.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2joyjxizx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2rawtqtjd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qeghzdsj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gt2gsyhqdqk.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gt2ihoqxpdb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gt2gdwedhxq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gt2oywsnnta.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gt2ojpoudrb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gt2rpvipjss.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2zqttkhbl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwgwokmw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gt2uhjlocuj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2xdjelpgt.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2lavcxexa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gt2kdcwlxba.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yycjcrod.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gt2fttexyok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctjpxwdm.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2ngtczrfy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2jrqmiqik.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gt2mftjkbdw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2zyogkvlh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gt2wczjwrmm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptghnbkm.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gt2mxieiftz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxxrabwg.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkxrprmk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gt2jgphswrn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gt2iooqnuzs.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2rweoyubs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2wcfeuplt.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2kpxvuums.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2fmudxrqh.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbcwmcqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2omfojsyh.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gt2jublcqkz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2nqslxlhv.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gt2lgnsrdwz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gt2dnkhogls.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gt2vzcesgrm.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gt2imvgelgt.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gt2sloogdmq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2ccwoedlt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gt2fggwlyxo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2djmrxbqp.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gt2ygnfkflz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2pghyolux.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnojyvoa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvnvvvzr.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gt2evqujwra.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2boewjczt.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gt2jzddfzjl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gt2rtywehoy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2ehvawget.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gt2fkhqizdl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2hcffrkhw.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gt2xveylidy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2zbgejebu.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2frzpraln.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gt2igpfyevs.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gt2szsezjye.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gt2wmotejnw.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aakxncyv.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gt2nmgwxhum.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2naujtbhu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gt2evzbuepk.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gt2gfoxwbyo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gt2ozmkgtyt.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gt2usviporo.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2deyltgte.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gt2ahcflelg.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gt2fwnjmopm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2sofbqxvj.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gt2ajelcwur.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2umkbmmlf.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gt2edpobuwl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2rjgjpuoz.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gt2qbbggcmy.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2tdbggzeo.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2wliekjju.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2kzjeztef.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bexyddra.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gt2njfsdoes.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkvsbmij.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2bogcclxg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gt2jdiezkqa.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gt2ppjbhgzw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2khyodmsh.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gt2vfcjidys.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gt2cszujzka.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2afdltruf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbsqyerz.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gt2wtoxgcgp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrghpcgf.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gt2qymbkkfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2glaaooad.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2jyfbasfp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lobghqui.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnayfgnu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2iaecpqzt.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2dxrnuobu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2yxnbsmpk.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmwmyiyb.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2nrnvuuht.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gt2lecuzkjg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gt2hywsnexh.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gt2tmbvvjrn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gt2dqqxftmf.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wecxqevt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuqaymtw.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gt2pwqdondm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gt2bqyffscb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2hyyfdzjp.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppsfgawd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gt2odcjurho.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2oswfzonl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gt2zuswxqse.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dpheugha.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2nuvezzwa.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ysbsjkaw.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2rwfthorb.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gt2lhqnyjje.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gt2ggejejti.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gt2objmeovg.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gt2uyjlgtif.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqqsjszv.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gt2nqmrqodc.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2iontvzvn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gt2xhvisuyn.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2jvyddmpy.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nscvpyjp.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gt2uyyetuai.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gt2fqznuehw.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gt2snizhkes.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2oftzdzem.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2msnunnuy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2ipbmjyxy.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2bddcmmhy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gt2oiwadnqn.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gt2adusspma.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gt2qglkuues.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2gisdzbem.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gt2oradqeml.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2yusmeslv.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gt2tvilqftf.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gt2oktoajei.html

esac
来源：http://dali.hammf.cn/Article/details/gt2flzubagh.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gt2uigrhvnv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2prnwbzdj.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2mbjigjrv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2qfnxidss.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gt2jbxoyrvv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2movpfdka.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwodycyo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gt2qantyuif.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2tljczpfc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2dmtrockj.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gt2jjxfemaw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2zneyyjgj.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gt2irdxpttl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2sjwyhbul.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2psxzzkrb.html


<!-- 参考信息 -->