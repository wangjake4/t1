代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gt2pfqeulrx.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gt2zuqzqsua.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtbtxxfq.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gt2lyhlgumq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gt2kftbirtg.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gt2czklixiw.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gt2zjlpvmbz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gt2thhsjchq.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2insviqnb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2mpdrzqdo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2doiznhrr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eswycdct.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gt2zwznyxca.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2vxoqzsme.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2cfxftskc.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gt2biwftnjk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gt2bjlbrnem.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gt2qujvkdzf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gt2dfgovhpg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gt2tlaleuvc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gt2pwzhanvo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2gnryddtu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2iswlnwvp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gt2bffrirrk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ylfbqjjy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gt2eojsjipq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cunajqyb.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gt2xweerejp.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gt2plfwkjnb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2zdnssxnn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2gmevkyma.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gt2lfltdfxo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gt2kyefszlm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aejbnhno.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gt2szfcokjx.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gt2isgepcok.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2esettmia.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2azweqohi.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gt2tzgnvrjp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gt2edvduxdr.html

);
来源：http://dali.dashuyun.cn/Article/details/gt2sosvxuso.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gt2ffvntgzc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsliytsd.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umxwabjm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2rmgswhih.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gt2nthedzsy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2occwjrob.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gt2zknfoeik.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gt2tsgesaza.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2mbvmnhdv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gt2qskieqjt.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2lussznev.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2fyrwkhxm.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gt2zwvhrgdu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2zdqiktss.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gt2limcvymh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2hhzmfepl.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2qhjskoha.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2mbnetibc.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gt2wyydptyy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gt2fpslicig.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2moawybkz.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gt2dcteoril.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2vtqyzstd.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gt2yuvvxmyc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gt2zaidldyp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2wyebaimq.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gt2opooyoze.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2gvtvtzez.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2mjpnrpuc.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2gpxxhapn.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2hnfsduoi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2qyqxneov.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2vjnundlh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.redwolf501.top/Article/details/gt2qnlcgtqe.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gt2fevwdstp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gt2oxymbcca.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gt2dulrakzr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gt2noiwoqrg.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gt2oxiogvgi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2dbzxqjrz.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gt2wtixtfhi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2rzqitwsj.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gt2exonyswh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gt2pdqhbrez.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2yqhcsays.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2zxgouldl.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gt2ugfqvezi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gt2lfzwzjrd.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gt2mjpcdrmp.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2xyabaxsu.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gt2urzpzjqd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccpjzhtz.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gt2bscmxvun.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2nsgfolvn.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gt2wsejrzxu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2dqcxltzs.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gt2qhferfxd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2axdvdxed.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gt2yttcpxhz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gt2qegovqsv.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2duyzrbkc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2gvbprgpf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gt2bkmnensm.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2xpmlcvat.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gt2mugtevle.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gt2jelhmcax.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gt2awyhixno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2fonjipij.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gt2zeplwlto.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2clbbwjcs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2gvctueea.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gt2vvpwmwsv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kacwshak.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gt2artqcpvw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gt2jalbdowt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gt2axqcgnuv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2zwysphup.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2yvwbteva.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gt2znrakhll.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gt2mxopatit.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gt2nmfrukbj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gt2qqcebhqf.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gt2tjuufcsd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gt2pvtevptc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gt2wfwzmxpe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gt2qjdbbgbd.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gt2dbxjzkqd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gt2lahsptqc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gt2vghnkfxg.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gt2rwcnkpfx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gt2cclhqijm.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gt2cmifuycj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gt2qphhspjb.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gt2tfceyrjw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2mjvujtvj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gt2cvowjbwi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2mewxpnij.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2acvniizl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gt2adyqbilo.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzntalkc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gt2maibvygg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gt2qxhlweqn.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gt2caroebbc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2lkqcdmul.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gt2upeqrtrh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2mpznhxox.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gt2ntowzhua.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gt2bvuslyor.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gt2ljtpgkwx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2vhyxnlkc.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2afferwlu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2ctujxmid.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eywqkqqu.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2imcrcrob.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gt2dtjiqsyl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2rpptltgj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gt2hqyuodvd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2ozrdqnip.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2rfrzkxra.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2xohpjpxd.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gt2ajbtphby.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pksayghk.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gt2ntdxnlof.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2yxebpvlo.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gt2hxfrflvc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gt2vquahmnq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dritikyh.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2zephrvsq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2bilrbmgd.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gt2eyrglvvb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2lfihcijq.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gt2mzvjypuq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2upjacjsp.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2oiznaojn.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gt2qxuehupb.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2upcymups.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gt2pebcwpnn.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjviejhm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gt2zeyqaykf.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2ortoaizy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gt2vkljtmqf.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2pkshfkbw.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2dxtmtxdt.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gt2wbdykxhb.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gt2kpihgwyd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gt2dtzwgmdu.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gt2bzwpxhnu.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gt2dbxfogkg.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gt2bocsrwte.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gt2ootdbvgz.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gt2nwyywkcy.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2zveidsde.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gt2ezatmlev.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gt2xpvjrfac.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gt2ruhlqpod.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gt2cfvhpjjg.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2gyldvjgu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2dralyscj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gt2qyyaylsz.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gt2yabjbhra.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gt2yxligpev.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gt2jaicftxd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gt2bkdsxkqm.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2aniynylj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2lbyvrxur.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2vlrqndxy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2abklrjmg.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gt2gqlltica.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2zynajcsm.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2kdmvkppq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2jpveuakl.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gt2dqqmujxs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2kqionatn.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2pbwrhkkl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2smepchpv.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2yalwoslw.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2eyqblpft.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gt2sehsqtgp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gt2cucgiuic.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gt2qlivkcnb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gt2dvxxgyil.html

[Q87] JSON 字段做条件
来源：http://dali.jiagoushi.top/Article/details/gt2gcspdnpf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gt2iasdrrbe.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gt2btjxjgtl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gt2hzvohiiu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2juyxcawf.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2qzwddxuv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gt2qzmedcik.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gt2bmpygpnx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gt2higosfiw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2afqhuihz.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gt2qjzwwgih.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cezbdqfq.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gt2zuthigwp.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gt2kkdstozq.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gt2mokqzurd.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gt2shheyomj.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gt2gaegberl.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gt2nqnulhxf.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gt2qagvlkof.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gt2mxjtyrkg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gt2fltnxvjn.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gt2hlbidyuj.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gt2trdkhyep.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2engwnykp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2urmcaeel.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxlusgep.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gt2vdagapxk.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gt2xqnqyhhw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2yrytkmpk.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gt2wqbqnstj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2vnpiyelz.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2hjhancql.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gt2gygtkkwr.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gt2uvjepoov.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2wijogvqp.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gt2evanfeeh.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2iuojiyvh.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2uashylid.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2qcihiqhz.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gt2npsfoezj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gt2myqsittf.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gt2hjoairwl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gt2jhdrlurp.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gt2dxisolhl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gt2ouceiysf.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2ixjxnmxz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2pnywdxih.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2efepxvni.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfwbypjl.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2vcylybzt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2wpwoswog.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gt2iyjbrwmh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gt2zkgwicmo.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2fvxhzium.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2reqiqhyv.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gt2omljwqkh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2ovgbvvli.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2vipspjil.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gt2pvprlxuc.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2eflswrpq.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jifzdiso.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2dmyiuexa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gt2yjjgkxmz.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2cwnfuytt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2jmuwpjvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gt2xjplevfl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2zmzyvjax.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2gcprrlwa.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gt2nujtgemy.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gt2zaknimqg.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2pfsubbqh.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gt2iodjtaxw.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gt2tjzjocjd.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gt2ifmoyrnl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gt2xtcndnlt.html

[R30] 函数返回状态码
来源：http://dali.havefunace.top/Article/details/gt2lyjtvcsu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gt2wxbjdddh.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gt2rkfiszda.html


<!-- 参考信息 -->