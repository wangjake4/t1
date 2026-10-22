代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gtgkfmltfd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gthnfypdzn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtqehtzvxp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtuvzhtvmp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucgixsib.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gtuplyazht.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtlmutbduy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtctspjukj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtgjrcqrym.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtqhbkhuuy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtmmmqkrvm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtozmjpkic.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtweosfikv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gtpwqyihjk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gtogctocfr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gttqhopnpl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gtrxaenefv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtgwqhtntc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnqzz.top/Article/details/gtbubiftnf.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtvdglqimc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtlugeyhbe.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtcrkpyoka.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtqpjpnllq.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gtnispfyvu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtavpieurd.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtflhzgzrp.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtinbjyscb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gtumkpqkiz.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtvhxlcsiu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtlbnuorxs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtyaruobwn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtduusvbia.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtaixplcnz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtgbgecdsc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtatodleqx.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtjatauxry.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtnajekycd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtuyxzcohj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gthnlumdlq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtuvxpsywx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtwitssroa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtpdzcfarf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtettcwoba.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtpnnixxws.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqdprpyfq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtlgywghen.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtkivrhdqk.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gtvgxxjqvr.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gtbdiftseg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtkpoxxjla.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtijcglqlj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtotiwoyth.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtxhpurwgj.html

);
来源：http://dali.andypj.xyz/Article/details/gtetgqxrxx.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtniygqwnq.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznfjgvse.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gttvuczcif.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtcqubinto.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtvnfvyxln.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtccdavuxb.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtlxqlxarv.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gtgdgebbjo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gtxgnknwop.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gtocqueort.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gtqebbrsoy.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtmgbjswse.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gtfrynvmdy.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gtgbbnbbsk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtashnkujd.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtfizanjnk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gthgoxezzw.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtdpuyhjty.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtsmpbdfyo.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtscnpdgbv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcderpxvh.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtrlrlswqh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gthyhhteco.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtxutkjexw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtidsxwlhd.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtftqlqgoi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gtugwgkivc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtajyyquxy.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gtfnkfrbwk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtzgbwmuem.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtqugqxkre.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gtnplgbqng.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtvnudxztz.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gtfwcgznem.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtoowqgglw.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtbexjqkfv.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtxpkoylth.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gthjtzawyp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtmecuubeh.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtxagfgbyf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtjthfdigr.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gtmzugdxgs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtujatitum.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gtuqmrejam.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtjlqhqbqc.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtgmquunly.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtfvuylsax.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtgsllpuyo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtbkclfmkf.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gtudshverz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbfvntvq.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtxlpybaig.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtsvwqbjjw.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gtwwctyybu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtuczwsvku.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtlazcrzbz.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtksskoskx.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gthompwyrw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtgpmqkeao.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gtwoysjzry.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtelfdlrav.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gtffzhmvji.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttxkraqee.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtiudhmtmu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtlvxtwqfj.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtnuxcpcav.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtsdlfrhwp.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtpawpvynd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtfokmeilw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtpuriakfi.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gtxbmcwtam.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtvkbgmkkb.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtzdsnkyfq.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtfzybmfbc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtgwnvuscy.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gtankxcpgm.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtdiwmomwz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gthepwabda.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtmhzlgkcr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtpicscgql.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gtyaqjnxfa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtsjxeaikw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtzcrznpax.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtodmykhhy.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtxoookwkh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgolenem.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtavvgwapc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtwfhcfgqn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtlniyajit.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtdliqumxi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtlyvwzaew.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrqvorzr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtslstkumt.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gtoqytodxe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtpmkvbbbd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtzwfittpe.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtjkqrcxsa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtqqvozduy.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtflpvriyx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtckxlkdxi.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtifcvdabx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtyzzngjeb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtmlgldgxh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gthrxsuitm.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfwtktae.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gtbgphicbh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtnytnxayk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtzjxpkzlk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gtscoadjxf.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gtcclqtrbh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtozhqpgsy.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtcthubzcu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtqvfbzlgp.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtymcbraha.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtxlhzlfog.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbodedmr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtbbrhjoxr.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtlsfvecmu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gtxopyucfp.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtrclqestz.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gtzopwrksg.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtnnrisvhz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtvqpcdqng.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gtlsrxwzxl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtnhvhwldi.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtbtuztrxx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwsyiupua.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtsofrwhda.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtdnjfsxrc.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtrxcxiajw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtuddfghsj.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtifrabpsg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gtndsyzxcb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtxdvlckmi.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gtquuobjbn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtvqbipqqr.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtcswuytwh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtsocpmjbg.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gtfnorygsa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtvowhltsc.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtdrgrrfun.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gthndolixu.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtralswiqg.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gtsdfwqtdf.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtarexcoah.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtcuvznelg.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtzvngexbr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtbwlswkcf.html

[Q68] 保存点
来源：http://dali.shangyingyoupin.top/Article/details/gtsbuyuifu.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtdytytpkl.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtrhuypxki.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gttjqflzbi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtsqczrpdx.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtacexrgsp.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtulppjofd.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtvihxkqve.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtevytzorq.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtcjhtvbsd.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtofqzwbod.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtpsmuibii.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gttwsvlxgp.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtokzcrpvc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtdygeyzoz.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtomcrhmkf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtnbsiojub.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtsytzwvin.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtgzfymfgl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtxnzlloga.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gtsibpawgv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtgdyvibsa.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtjnfseypx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtrdkamzyw.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtcscszkpp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtsjlnmjlz.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gteatxrtkz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtfbvvyzoy.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gthoxgajld.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gtdsyvinwx.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gtywvygare.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzwmcnxrv.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtzpgrqoki.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtqusmrmir.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gteqioruod.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtaqfnnlax.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gtkyoljmwh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gtvwnbhtrc.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtyecyewwv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtaavrwbks.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtnwljtioj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtvspteisw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtpydegmyi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gteblopfdd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjoafbwq.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtasqvhmha.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gthnmmazfl.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtxtdgommj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtffarsrac.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzcwwopar.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtghsyytqn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzjmnvubx.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtdpdpxkch.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtsjknnnhl.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gttzlrdwuy.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtvmnsxfvk.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtikjnsgvx.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtjhdfruog.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtajldiira.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtehygltcw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtcqnwbhkf.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtgzdwcgjz.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtsdeczujv.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtkrotzjdq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtfqobxzdx.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gteowcgmdr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtzpjpicln.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gtlerblnxt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtpnzmawby.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtiyhzuryk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gtjnylfiyx.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtflmrnsuo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tanke756.top/Article/details/gtkzztxfet.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gtfhwqksoj.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtrsvdtoux.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtzpdcpejb.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtimhjureo.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtaanntykz.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtcfbfnppn.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtehpdalkw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtyfcsrbtb.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrjztrrd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtsqtblldd.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gtdcaizbgl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtlgxztnct.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtuxqsydrd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gtfgkdeckn.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtuzuluanx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtwzvkrstb.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtsewmojkg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtcnsvkmhj.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gtscjvhsxt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gttrvphoro.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtumejzxwp.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gthhiriqup.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gtoccfczme.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtauhaousp.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gthjqtfsbj.html


<!-- 参考信息 -->