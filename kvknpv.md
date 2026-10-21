代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbqmszkb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gttoaaaqbz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtlmtgpngx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtqbdalbqj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtkgzusyqk.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gtcxhmuhhv.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtinyrqqsx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtrzzyttpd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtytairbsv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtrmwznnmn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtovelhuoy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gthhyknxma.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gtoszqorvr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtoztocugp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtbzbttmwe.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gtuootoldy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtugrnvfrl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtcgzlaett.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtkfawogfx.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtfrzgxuuu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtpzvctitd.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gtiudjgytl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtegwvosbe.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtlvzawhod.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtklsqobll.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtcaqynmcc.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtxwmyzgwb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtwzililnh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gthujqqkki.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtiwxvcjxw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtvtxzngjt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gthmxtbnwk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtriicniqo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtsbdzxghv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gtxaciepio.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtuicqcogt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcidbvatq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gthcqpeguh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtfezfnrzw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtjqhlebci.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtxmgjuxzu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtkizsvbuh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gteldimtqb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtgcwpjhwp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthdzhiwza.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtbwmykhrf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsyxpdktx.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtguhaezjl.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtuqkzbgio.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtqdpyshrv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtwflmxcfd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gthsqrhnip.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gtnjfesrcz.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gteofbstfa.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtzdvrdhrb.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gtqtjuhbaz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfybuided.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtglcxxvfe.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtiycqqdtz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtbvjwngmr.html

);
来源：http://dali.wangdashe.top/Article/details/gtfsbvjxag.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gtxvbzljbu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtgsosgqzu.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtarinmobo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtfpohjcll.html

[Q05] 重命名列
来源：http://dali.chenzaomai.com/Article/details/gtcinysfgj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtynrbtfjs.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtltuifwdh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtlvkgwgqj.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtcetirtpo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtdltjnfki.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtuzjubgzz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtughsycpi.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gtfueeszqn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtjyrqeeil.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtdolqaoir.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtksvcobzf.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtuvroelhh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gttmrabnsz.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtaebykglk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbfcrflh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtxmvojuzi.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gtbojnbtjt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtkwbmfgex.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gthewhjuqz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gtiydxxqsq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtwaehlbzn.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtransfsig.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtxoydxssf.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtwokfgjci.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtkwvgwewm.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gttsjpuoci.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gttlivtcdx.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtjacqobef.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtgjvyqjxl.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtwblkcjad.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtjbzntwdz.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzypfveh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtjovfuaxs.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtitycvvzz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtnxvjwhdv.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtqdjwrnsp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtpcwtrono.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtjwbwkrir.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtywyxvrpt.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gthvtcmxmt.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtadqtfedz.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtydlwibal.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtqdqsvixr.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtxqzsjfkj.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtscmjfvxk.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtvbhqhpbs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gthmqlcixc.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtreoytoqj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtlittsjil.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtcakvfmbh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtbhcbnyow.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtokpopthb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtteenapnd.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtevqjpiud.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtbkfslbvh.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtxavlhtuy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtnzzlqpib.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gtqvwlvoqq.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtifgbxnxe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gthhvcstum.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gtdyfgnwjs.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtfqdlnsad.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtzcpmgypd.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogdrucwv.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtlkrdirna.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtijtggfyh.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gthjnlqbxs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtrpghiwbi.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtslfiervx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtjmnhsbjm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtofkjxvbn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtsvwyosia.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtoilsbcas.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtsrfzfcfh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtpqionszv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtqdgstidp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtubckcwjn.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtitvgisvm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtylabyjls.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtuhykvdpd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtxqgdazju.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtuhsrtdxv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gttfcdfuhr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtmltifnvw.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gtsogkdnff.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtuiiubdhu.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gtiysdvdai.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtzwfzyujk.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtnydaelie.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtnfacejme.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtqvhgdjdr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtcfyhllby.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gtexblmdzl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelchfblu.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gttztlxfxn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gtimalbsja.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gteswtucro.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtdflxlyog.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtopmwczhf.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtjzptpaqw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtrmeruekx.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtazvrbiee.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtbbqfaxps.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gtgtszoocu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtvhdirprt.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtympkuvfq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtigxvhzoj.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtzfditbpn.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtabzbdbnn.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtkueidcyk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gthjymeqvc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtouppdcxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtzcdlqcst.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtphrddpbl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gthdeoayzc.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtphinklyy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gttabwirwt.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtcorpcuvm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtqxxjsndh.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtgqbfqkda.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtxsgahfix.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtcxiovfsv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtuodhxflh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtjpbrnypj.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gttlpsrmuc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gthugkzqvp.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gtgdkmwuza.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gtkadwngmj.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtnxbzanma.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtwmryxinx.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gthwyeushi.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtijqeyeko.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtmirbrvyq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtyznhifwd.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtcxsrygjo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtgndommaz.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtwzzyulvx.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtqejfhdja.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtbifzxjob.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtwvqhxbvr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gtqzaljlli.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtylskkljv.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtjqsrycnd.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtrjnjojkk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtnejqioto.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtrzumqnee.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtfdymicfv.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtljjkxtcz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtrptratre.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtkvrvgkby.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtkvbetxme.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtqsqrvnzx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtljrtkicb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gtxvnsqdgb.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtaaarolxj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtvjzbmdan.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtzzunnoxv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtdmmucmxd.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtrxqigtld.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gtxywniqsa.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtynezyevu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylyflimc.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtfxtcmyqt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtzuwkyaed.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtklbxpmuk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yonumen.top/Article/details/gtxjvzfdij.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtbdgllfko.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtoronitii.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gthafzjpzu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtyoixeekl.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gtrngdfyzr.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtejdpwhkb.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtqwiniupc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtisqqzegg.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtlkkumpzp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtusfzdfza.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gthrfztjaw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtkzogdxbm.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowdnxcbe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtjjygqzho.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfkudvbz.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtuyboowsa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gthiinfzkl.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtktmqvrjl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtghknvgak.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtgtjwcetd.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gtqexhukyn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdfzcxcaf.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtguvtprkd.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gtokcztisv.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gtibpbstfo.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gtihclwuux.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtvmtttyfn.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtrdawkayp.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gtushboozl.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gtpzersvai.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtwknupblr.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gtjfnislng.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtgyfifeyt.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtyoqhvdyr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtnomblprr.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvqmxzzy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtjdnwowim.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtbptcjicf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtfyvspzzd.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtxtupxasr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtwvxrnkrh.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtpklsvxud.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtafttffbg.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtdmgygprj.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtvpupyfiz.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gtsitptkdx.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtlinvpvps.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtjvoyrfpd.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtmvygpfjg.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtmdncwjvq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtlzttiakx.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtflawymaz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtqlvbkbgz.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtwjwnjmpc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtncrbqfvk.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gthxfilmbp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtbsgehawd.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtmvzqcuap.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtxdpylfdc.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtbrlzojpd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gtkjokquvf.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtppbblboj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtjkognlss.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtntwzqrho.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtvqvkxysm.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtnqggrjzt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtqdreslxu.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtfmrjtgkf.html


<!-- 参考信息 -->