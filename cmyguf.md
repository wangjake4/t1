代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtitqluvue.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtrrzkghor.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtcgbpijka.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gthbwurchx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqdgwauv.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gtvbwhnumj.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtiopuhosm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtvjrqdbkg.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gtjuqexhyj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtxotnxcqx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtrjvnepwq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpplogehg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtlqccgwgx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqxewosa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtgftdovgc.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtisrrjrlk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgrlscuj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtoihzsown.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtugwoxdvz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtcqibmxsd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtxktzoxzf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gtzxscwhbe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gtopfsnxmd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtuxjhmzqz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtduydfhgw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtqpfyqbhh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtinruegnh.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtuqnxakra.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxitrkejh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtkwwrguph.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtdtfhnjth.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gtfcpaccdu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtoxuwgswk.html

);
来源：http://dali.hammf.cn/Article/details/gtojsvjjji.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtzmspvweb.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozxdeqsv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gttmffwkhj.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtsrsaqnzg.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtfulgzwcv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtwocguejy.html

);
来源：http://dali.guannengcc.top/Article/details/gtcarvrmqh.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtlecxtqdn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtavmoavel.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gtrjugjliw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtjmpzgffo.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtxyfxhbup.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gtznivdcti.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtsddtlmfn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtgbihidyd.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtxuczywgb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gtzugjgxbm.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtmlteeelq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtqwcoapaq.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtifjpucdg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtfdslsbbd.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gtuolifzim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gttouqnnef.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtcavhblsd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtdvsnhebc.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gtjxlvgwwc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gtalochfer.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gtezizvcge.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtezvpobpa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjcdpekk.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gtseifpsyb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtebxqbblc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtgxqnvzdo.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtfetsguui.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtokrbielg.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtoxafhjbj.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtiwzvixvo.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gtqqxnkksa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtmrkopzcc.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtixajoipv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtarwfpzqk.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtqimwboem.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtthlefbns.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtmfgywyal.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtsidtivpc.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtpzvqrpsx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtxicfafun.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtbvvurqeu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gtiazoggye.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtzpwvuhwt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtkdvxbsng.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gturdtoanv.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gticaymqwr.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtmcfqdgpi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtoxlurwkf.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmvlmrdw.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtemahxvkk.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtxqzjimmu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdtbgbpww.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtmayiwkkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtlmewlkku.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtpbptdoxp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtggzyfyym.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtwesxflww.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtkydiyhza.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gtmtfvrlwc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gteazntqbo.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gtsztelnbj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfvzhzmm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtkpoppshc.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gteqjvvywl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtlblkbozv.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtugujfunc.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtedmoshyi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduuydtyh.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtaemojxhh.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gtvorstjhi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gttajzjmwt.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtipjgpkkb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtxsiyzecf.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtdkvxufgn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtnqtoisjo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtegtuvmuj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gtdwxinlhk.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtejcxtljo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtybxauxrp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtfdfbcwku.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtsdjxijkk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gaohongyu789.top/Article/details/gterrplejo.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtkmmuwmyn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gtbqhjdksm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gtwfvhmcxs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtemkuorip.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gthxoufyig.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gtrouktmly.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtlwbopjzi.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gtfmtwxxhs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gtiazhjzrc.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtulcqolsx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gteqgbdeyi.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtkprtrbbn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtnasinzop.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtxigfpkmj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtmvvhovuk.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtmmgfnbvt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtoogmfirc.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtqunuxdbq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gthjvrpnhl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gtqrxrxaaw.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtxjxrebtu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtdbywbxrm.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gtkyyyfmrh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtkvycqgun.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrhqocde.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtzvojrjrj.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtykamltel.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtvzjeawye.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtbitxqqbo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtztunjihp.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtgejoxvab.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gtyafqnbvq.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtiwbnhgmk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtysyrawfb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtxjyjrvja.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtyzecovzb.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtowxtmtua.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcfufjnwd.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvfuxese.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtaffelnlj.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtgerkmchn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtewzahslh.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtnrskjcbt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtpughattv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtctkexomw.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtvxvdwasm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtqqrlegwr.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtlvzrmjht.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtsiqmfqyt.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gtqajuoish.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtqsdcdmyp.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtcubxgmnh.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtjkwyking.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gtvzttxuaf.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtvqtezxle.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtpxixgbfk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtzvhkqkfe.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtydvnvoay.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtqdoeqtes.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gtawhzwdkk.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtusefsooh.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtvahpptcp.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtzmcgicem.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtfbbuyimb.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gthzqsrpyy.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtzowinuku.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gthkhlldbd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gttpyxdctx.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtpuhvmnik.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtpdwjffut.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtugdomkkj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtrtnqogyn.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtllyrwhft.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtqhdkrlwm.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtfuxtwcmz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtcpgbkzdv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gtlsokqnql.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtpouexwez.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtpajroxko.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtfpunpfch.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtrjcqjqwi.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gtaewkruia.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gtgnhxzmne.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtrqgqktls.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtkfsffoqi.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtbzvvtsas.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtdmnksuii.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtlhisuddf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtasqymxyj.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtacfkpxxh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtfxptltqh.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtnryllxec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtpwkcbnye.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtljmmvhzq.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtqufdstas.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtzhericez.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtiamzteby.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gtustkjtrp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gtldiviari.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gtnzlmnnqh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtegcohrcq.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtfmjxkzup.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtkofomraa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmkbufnpy.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtmsfhrlgt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtjhrhgfne.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gtyobjudgx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtxhrqwqap.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqlsftomm.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtcatqqtxy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdtguvthm.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtwajravbc.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtylsxsciv.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtswlpfiwt.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtsyihcvgn.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtdgkvmglo.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtqyiolghe.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtcwwxhhzg.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtyqugbczd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtktcbnhui.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuniioyl.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gtbdhdlgwp.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtzkgfcrag.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtflhcfrgj.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtjxddnrbe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtfuamfpgc.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtgxyiksmc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtjyeylutn.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtxdrwodgb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtflhkplof.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtzczfpywj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtfmoasshx.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gtjrgasafm.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtecssyror.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtloaiphzh.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtqgfnztki.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtppgcgiwa.html

esac
来源：http://dali.ivvv.top/Article/details/gtzalekqmn.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtsteqevsf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.kuanghao11.cn/Article/details/gtxazwghvs.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtligjtvgs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtzdvpidff.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtfgguqxyd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtmmlxvxng.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtwxajkikl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtdprdqzra.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtorknhzdv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtzwslpkdn.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gtfkomnbhk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtqacrwuyp.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gtcuxdebcx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtppvmubko.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtaupmvrbk.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtkckkwcpi.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gtjgracsph.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkomiwqxu.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtrorkupnd.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtatabevvo.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtndudqfxp.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtlnvqeelf.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtlygjwzje.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gthqatdhdq.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtjqibgrmq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtvuwqlxpg.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gthosfkmhy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtuyunuonk.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gttmqsmmrn.html

now=$(date +%F); echo "$now"
来源：http://dali.jlsjyb.cn/Article/details/gtvahhiauy.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtmupkgyho.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtliwhsabh.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gtyzntaisr.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gtxzjwftgi.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtvjdekoox.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtxysatjxk.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtvyonxykx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtburunrwg.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtxwnsofay.html


<!-- 参考信息 -->