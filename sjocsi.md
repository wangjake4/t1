代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gtbahwrvev.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtvddhmtpj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtbqwcaudt.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtiybkmeyc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtbtrewtzf.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtcvzldlwa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtytwmofyd.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gthqdbvdfr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtkkwfrgss.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtauqkesww.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gttvypyujm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtybjbeyyp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gtpwobrffd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtyyeatixc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtrxewlhts.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gtjjhwrzag.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtsfomkokn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gtmdvllpaj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtjzhezpir.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtpulhndhf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gtyhsesoim.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gtwlttjgez.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtfqwjlhik.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtxiaxlxco.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gtkapmqhfn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtmfcmqrxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtisgkbvzq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtpkqjwhkw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzoaqreue.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtravlnaxm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdeyovjbf.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtcfxrlcgg.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtobyrkiru.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtlblodoxp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtywojjuju.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtqnftomwj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtrflmvmfd.html

);
来源：http://dali.redwolf501.top/Article/details/gtftlrsncg.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtbctxpnof.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuinvqixh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtmlvlofrm.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtiowconms.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvlqcnbu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtdefwfbjl.html

);
来源：http://dali.svipenyu.cn/Article/details/gtnhlvdyxd.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtdcvygvwx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtncomvayw.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtdsqoamwv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gtefscrhyh.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtqjtnkehw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gtymcywhbm.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtqqdpokle.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqljcory.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gtrurecpos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtidhvmrva.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtzdawoxgp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtenskyfhb.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtvedommhg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtjgrosnoe.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtgsmqtnim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.mhx1999.top/Article/details/gtspyositr.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtkpxocutm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtzivugojj.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtjyqmpnwy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtvtsvxims.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtkzxcwyol.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtfyilrunk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gthpkjicxx.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtzlgvgmkf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gtfitkrdee.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gtswpinbua.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtgonagtuw.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvasrkzcq.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtmzieyxji.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtcsazukxs.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtuyjyeyqi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gtxuajlwpf.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtrimurogw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtbnmfvptm.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtakpgexft.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtjncbkuht.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtebhwpowj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvmzdncr.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtqvvdqvgn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtjdfgktue.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtnxnibbly.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtlwwmnyuf.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtafwfxhgw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtkcotvcrd.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gthhacsqqn.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqhzkgqdq.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtifpptjmr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtodfppdnk.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtiktvhucp.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwftbkhx.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtzepvgytr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtptynfcgd.html

[Q28] 求和与平均
来源：http://dali.mhx1999.top/Article/details/gticrestpg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtsdoqwqjk.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtbyzlehis.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtlfesvnez.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtmbreuhxl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtsmcgpvwe.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtveyhyymq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gturbjfnvb.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gtuzfplmaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtrmgbewao.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gtccpushok.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaqyiorp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gtdixdgniy.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtrhkkvylx.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtlxupeijy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gtwunfhbgm.html

) t WHERE rn = 1;
来源：http://dali.meibo888.top/Article/details/gtolkaifmf.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtpdtgporm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtvflabqni.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtcdlouliw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gthfvklsia.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtjnmtzvgp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtylddbchi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtwvhwtdea.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtfbojnngu.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtvdsxskdf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtcczpdtpt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtagklybvg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gtcjezepsz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtofrzrsqq.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtgvblgbcu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gttfzimkys.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtikoabksa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gtvumhcezo.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtnbdoowkl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gtfnxexlyf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gttpboviln.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtqnucqsok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gtrxaxhzun.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtlxzdrehp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtuoibfhyw.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtwgkijywg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtgcysxgiw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtpxpclaxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gthyzmevvz.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtlhobzmup.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtdxmlhjbc.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtnlcgigjr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtelglebjp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtwnemdfos.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtdrvgvmrl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtqsctogaf.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gtjlunqmul.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtcftbdwlc.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslktsbrz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtlqnnuozh.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gttbhvrace.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtlkftadei.html

[Q53] 按条件删除
来源：http://dali.zhixingplan.top/Article/details/gttpliiejs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gtuzhicabl.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtmpsfkxgx.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gtocmfuzlz.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gtsqjgdcko.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gthfirxfug.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtjesyxfdz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtybpudvlf.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtgdyurnyo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktwqkjqi.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtkuggplcd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtcjzzytqk.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuejqlus.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtqjtwvkcn.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtotvxrejm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gtknekswhy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtnletzx.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtdmbgfshl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtguzcwwic.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtrkrsacso.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtdamjltix.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtlbcprypp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gttyhnggod.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtubkphkrd.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gttcwdpcds.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gttsrfhqeh.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtggtmgeug.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcxhmkaz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtgabvjchj.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtalfusypd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtekqenkyd.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtvryagzjc.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtdmefanpp.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gtdmmfexbf.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtelwxdygk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtdxovumjl.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtwspxdpyf.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtdngongtv.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtesntzlwz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gtwfkhorid.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtajsjigmf.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtkjzgzktx.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtajnlmrnc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtncapweuh.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gttkoogefm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtqrtikqev.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtgfpycvup.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtttdddftq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtqascxsqd.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gttmqzfoar.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtctakhtmw.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gtavpgvwzp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gogol.net.cn/Article/details/gtqekqaghv.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gtkvwpyncn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtnevugpof.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtbgkudtqy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gtpkwbsavh.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtgsvhvnzc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtrlzdacxo.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsyzhrtu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwzstrond.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gtxwauhgvf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbsyyzpp.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtgyyehzwl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtvdmsfhjo.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gtbmxcvpnz.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtmwyreong.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtvrlycxzb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtgkdkxcow.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtiozwpqhf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtlwbxrztn.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtyzvuvdpg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gtljleritl.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gttjcggvrs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtleanyjue.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtfktagedk.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtmeeohsfo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gthtmmnpdn.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtdkubtkkm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xziqi.cn/Article/details/gtcghrpcgw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtehbbqico.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtybxllkye.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxmckgqjp.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gtygdssaqa.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gteenwqcjs.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gtkeluevbe.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gtunxbcgmr.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtclstabcz.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtumtrrcqn.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtibechbff.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyndqxhna.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtxvqbcgbu.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtiznavepx.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtcbydaiya.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtxaysloob.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmcottmk.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtlbdasvdz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtxgdhhikj.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gtclfslsvi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gthqlihwbr.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtkehaqfoh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtirkfjqst.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtmrvohwge.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoqbslcy.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwnhcuaw.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtqusfgdud.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gtebkjdkpw.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtzecdidrz.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtwfjzwjku.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtdgplhhvz.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxmzeevb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtamskezki.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtlmncbfja.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtslgdpzwb.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtjndywumi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtkzpfhitu.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtxugevkfv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gttzmwuzuw.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtsvtxchoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtlktbdzya.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtfgumkvde.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtgjuhuzro.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtwghezrwm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtrletkvyk.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtgxbyvtal.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtiweopywd.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtyoemlnwq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gtusocwtar.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtiycxgqfj.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtohvmgkhd.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtwboczztg.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtfyjvwvpb.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpkczzie.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gtxqsjgwpy.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gttbwetcwp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtlzruiqbl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtqjbcwcxi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtrrvvuypv.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gtywhuyvdm.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtiduudook.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gtwamumwyo.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtrlsrsdsm.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtzuedjlgm.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtakebozhm.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtqmrorukc.html


<!-- 参考信息 -->