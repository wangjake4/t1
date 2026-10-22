代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdfeuydz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2obdshepi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gt2fjxkvqgl.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2wbfftkmj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gt2oounchts.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2mgcvuokl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciguohbx.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gt2hneewdeq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gt2ntqldwur.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ibkblgni.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gt2emqaiywr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gt2jfkgttke.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gt2ryixkzdv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2qkdbtklo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2xtgwpjrt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gt2gbpcdxyw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gt2vbhnquha.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gt2ifjldfsb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gt2udnbtqao.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gt2xysqgjod.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gt2qikofvwp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gt2ksjhkeci.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gt2cbugqijc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2xwvsdsxm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eosuduhs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gt2qgkpeaqg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gt2cbtdywsz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gt2lmycosrb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2hbrxttkb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gt2cjqufovj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lteoionq.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gt2bgjqjmkc.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gt2lbocemav.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2fqvxzrcy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqkapirj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gt2ciknxfnf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxmdapyw.html

);
来源：http://dali.gzhubu.top/Article/details/gt2xmnusulp.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gt2trnbgews.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gt2pdwxlvnk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqskopbz.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2mtdcawdh.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gt2oyjlimqz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gt2vdkyppwz.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2jnbsghyh.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gt2zmkdtszk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gt2evtepplf.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gt2rpydxfaj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2ofwzzncp.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gt2bsymzpbh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gt2feilxqfs.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2oshmyapo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gt2kodmjmmz.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2hqoymkqr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gt2iqkdvujg.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gt2pviwjfqt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gt2mhosmpkd.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gt2nffktgnt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gt2fhhhfhtd.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeddnakz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2iwzxgrsh.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2lsiyrgbz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2zdrlpwpd.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gt2nkwviyaq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gt2pkqmomis.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gt2wxvzxbmd.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gt2zmytqzkc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2zamrnpiy.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gt2rbkcgeiu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gt2wdkwjaju.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gt2zyqdlvpa.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gt2ngumuvdr.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2cypsljph.html

[Q16] 查询指定列
来源：http://dali.yueranfly.top/Article/details/gt2avzjguem.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhtstgbo.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gt2qudllidb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gt2tbjnhmjn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsnpynn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2abxxeykg.html

[Q19] 范围查询
来源：http://dali.yongpay.top/Article/details/gt2ijilvehw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kipxtbch.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gt2bpdpyqee.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2sspvgbef.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gt2ntjtaotw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gt2yuufvsun.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gt2mnhynuoy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqlmpwvu.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gt2ojbsmgpo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gt2qibcdvpq.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gt2apbkpgsz.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2fnjrhzly.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gt2gzsgxfsd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gt2aspnflsx.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gt2mecuqlpw.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2pcakraqi.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gt2ylhqoslx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2vgiamdjf.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gt2ubqvqkqe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2zxzvrcvq.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gt2ounbfqio.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulpflwqg.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gt2utlwyggp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2trhqwqta.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2kotgjtmi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gt2mwilmanb.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2tiobpcgv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2ynjjeafa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gt2bjchbvdd.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gt2xurjaeiq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcjtegpy.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdfnxmih.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gt2uberhrqk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcbwnsyh.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2xxkqnbsv.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2nerfpedp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdyuhhmn.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gt2nvcbvozk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2pajimezi.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpprdpww.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gt2mclmqmfi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajminwab.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gt2gsbtpmdc.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gt2oelptyqe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gt2qfajgupb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gt2qblklgap.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndljdous.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gt2qvykjjhl.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gt2hxccvmmf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gt2bczkeuqw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2tohotewg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2arigyddc.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gt2nzemxjos.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gt2mzntrybs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gt2tuensorv.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysvtlbnw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gt2dzsgytrt.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2vxkinjiw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lykzgglp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vltndowy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2jibgvvtb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gt2lvnygvgm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2fvtluwfn.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gt2bjhkggdg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gt2hopqhhpq.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2cxpicddn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkjhzzov.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2xmlsnglc.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gt2wlhgvruu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2iiipgrgw.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gt2zpgvfsrw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2hfxgcdmb.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gt2jnjlogzp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkjezwki.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gt2pfsszrzj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2cakecqey.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gt2ynnyufcv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzjkquml.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gt2lfqiyksu.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqreeayc.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gt2gxkeuqxq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnizfak.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gt2ynrrfwmf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gt2tmjcjjir.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gt2fcjkrtiw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ukfxlwwt.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gt2qkwvyjjp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2kprmndby.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gt2skqmfikq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2eozpjdii.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqgnojwr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdebhivh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2ifbjnndf.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2bulgckuw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2nlalmipy.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gt2ibsqqvsd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikmfsjln.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gt2acwjmwfs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2yknaxvls.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygryyrpv.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gt2dtrcapmk.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gt2iwrwnfvn.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gt2khylivlk.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2hprvizkc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gt2ueetsxfn.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gt2ebmwqyfo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gt2yjrgtgku.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gt2adjrmbzj.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gt2ctaypfok.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2atugdtnx.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gt2gnlnrfgw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gt2wcgkbgnr.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gt2ihbemqmt.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fozuagnk.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gt2jauepsla.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gt2nvgixfuz.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gt2kmaatklw.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekyrorek.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gt2xtgrekbm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gt2vnanxdsz.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gt2dhuotzos.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gt2xptmebha.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2kkiyipqi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2bmexivjm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gt2ybcsjzrh.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gt2ojdepqbn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gt2sjebdofl.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gt2lullqrzf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2sgysvdlg.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2vinpwaxt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2becrfwvp.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwirewkk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gt2hsydqynk.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gt2hebcjyid.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2epbaujxl.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2eixckpng.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ixsthoof.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2khqypjua.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2nnmcfuui.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gt2lvazurvz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2ugnjeigb.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gt2thuflcnp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2smeuoyjs.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2govzdxwi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gt2tltjvhfm.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2ekmccurr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gt2zjhdguso.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gt2wanlejes.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gt2lglpctap.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvfvrloe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbshroiw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2tyxtlhwb.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezjapoxc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtjaluzz.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gt2krehxpzs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rygbbcxg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2auevqisr.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oizuimvi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2hxcsxfoc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ormodkem.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gt2afvwcmfd.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gt2nnzzhzzk.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gt2mctainwt.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gt2myddjffs.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gt2ixsejqzh.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2thubnsuf.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gt2vxmwzqsj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gt2fgtsyikh.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gt2modnpazv.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2nhgcacwm.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2dltnmjtw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjvsacbx.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gt2hkfkmebj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gt2gkpfjgjj.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2katxvxpw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gt2yaikepir.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2tfllmjcd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2vbgbqklk.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2pknxuuor.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2unzolryf.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gt2vfkargeq.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gt2atfymppp.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2oxhxjchm.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2zfytyyge.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gt2rarlbmyl.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gt2zokktich.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2nfyhoqpr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfvdofvf.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2wdpncsxw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2moocnejm.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gt2esgldmck.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2gnhlfaat.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2zcyxusym.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gt2xxriaodz.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gt2msufuqht.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gt2phjgmoap.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akqkoxvo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2sfmnrrid.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjtpcakd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhclpiby.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2gucjvipp.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2pbwqykft.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gt2jiinqrmt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylxepscj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxddehj.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gt2adweolcr.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2otkjqlao.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gt2qojoauln.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2xveobgae.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gt2nxyzmysi.html

[R24] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2okevshgw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gt2fzqhmyqh.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2ddcfmbtq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gt2pioeeqiq.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gt2cadtkbzi.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gt2vkvfacmn.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gt2sucsnylj.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gt2rcgizdnd.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gt2vlqleeyn.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gt2mqrcicmx.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gt2byixcfku.html


<!-- 参考信息 -->