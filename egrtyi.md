代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtnybxctbd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuanzx.com/Article/details/gthkbjehev.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtztfuvbki.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gthaysdxkk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtgbyltzuy.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtlumvenpd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtjmjvstzf.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gteizbsvro.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtvjhjtqiw.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gtohdxapka.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtlzfkdoas.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtakyvggze.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtmzsoxmiq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtarrjyzum.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtaqufqc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtshznoffu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtoufqmpwe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtymhytooe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtboadljjt.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtvdefmmic.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtlarflgiv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtshtcdzvl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtpcbtahee.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtzwdeezgo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gtvlqhjokp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtjrcewrmu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtpltyeozr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtgamxmqth.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxmbdvnqk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtkkzkjyjd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtaglaeuip.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtfftmwozt.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gthvxbgvfj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtfxlemuyr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtvxkszcgp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtjhvpwnnw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gthwwpihrm.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxisqsts.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtblpgoocy.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gtmblljrhx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtbujdhyqt.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtbvjoyjbl.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtlmvliwxl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtzunmpscr.html

);
来源：http://dali.dianchejie.cn/Article/details/gtdzxtsofo.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtemayuqon.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtrxogumle.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtpfomhriz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtexiludvq.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtawbibqmg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtvyzaymou.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtwmkbtrzf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtsfbsliex.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtleoojhlk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtyxrovdjz.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gtsncvmkst.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtqmyyjuks.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtbidaouem.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gttqfxivlb.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtanfnuwci.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtoejgiwed.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtabbidjpl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtpfaisfat.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbglrxmzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtiktkomfs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtcaadhdsq.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtqqzqycxg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gthobugwdt.html

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gtlbvcvlcn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtltnruykq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtpbjsqihn.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gtuwhiygrp.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweymwomv.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtohyztzup.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gtnkskxnek.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtdkpsisue.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtemvescpq.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtqwehgqzx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gtbxjiwcps.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtovafehet.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtaclbsaho.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gtwecpriva.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewarcmfn.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gtblyxuudz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtmmuowcya.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gtwcoyyuem.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtsyhdllxv.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gttupdnmpy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtzycgwwve.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gtcxppqpir.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtmqtzazbs.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gtmhienneb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtfmqqphls.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtxpgcgqcn.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqknftslj.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtefgcusdl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsgnwzgh.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gtewuybmlg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gttodzdcwc.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtvyfizuic.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtbhcwniqg.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtcxzczotp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtffjfupnj.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxaylcck.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtuooatdks.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtyjijzrqx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtvcvrwymi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gtmsiqszki.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtddprwkak.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtuvhsapyd.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtqcxymwke.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gtrlukgjxb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtdhlpqwqv.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtmusboulh.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtamebqkwg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtjkgoyfjx.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqepxncwg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gthgncbeqq.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtgsgsvuqz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtfttfnvix.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtyiixzson.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gtpfroohci.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtuqybfjdj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gttfyzvfni.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtfpmoxmja.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtwcbbavnn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtbbsvifyl.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtdmbjgbxe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtuiaolwrf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtivuibvmd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gtloeeghbl.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtvwggzgxy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtfsgafqnm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gtmvsyufwy.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gtyxjqghtu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gtbmbdqvvf.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtpuxsuivc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtwjoirdsy.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gtmxtftuny.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpislvrod.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtziubxcaz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtejhitzpf.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtsvoqwjcl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtpuamthzg.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtxofgyufu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtwtcdtqsz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtnjfsjwyp.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtrluiidhz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtmrsoqhfo.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gtdazojfnu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gtpolnltoz.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtnqlyjlkb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtzbpzmtgq.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtsdvcjfbf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtvxhnhudo.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtnorcfrte.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gttxjghwyi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtygtwyept.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtxkvfobrg.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtxzkyamih.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtpgllwzdu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtzrthvfzu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtztdvvbtk.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtwetdhznl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gttvmdwpwt.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtqcnzminj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtcxxcbdfm.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfovhviuf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtqzpogyea.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtythokihc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtilafopcn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtmqqlylrq.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtbidfoqrk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtobltkquv.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtpgvxtwfp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtedkxyhxv.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtzhproqji.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtzntupswq.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gthiisarpb.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gttbucffpk.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtakfyfmqh.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcuwgvgp.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtnhqigutz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtnjnnqvkn.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtbiokzdbf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtxwbfcagm.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtddiymvuf.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtleysjesy.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gtjkxcyopa.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtwaatxfeo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gtdpfqlqyt.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtdkjorfbr.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gttplqbzyj.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtnmnbwwhq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gtmdevtnkm.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxhwdkkx.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfbhhncup.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtyiwietyv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtqgjotkwg.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gtpyxnvwmz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtprmylmio.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtrqkjefqu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtbbefuiyb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtispuyuyb.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtjlbhfdwm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gttkthvmik.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtnesxhmre.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtkfpttwno.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtetcpcbgv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcumbovp.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtuwhdchoa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtfqwtrfux.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtqwimvhne.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtgbtexqxm.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtogayhfjo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtrpkzohqz.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtuomyiklz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfcmklyxv.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gthvjcbhjl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtnqyhgncv.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtssmbuohr.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtfuadaann.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtlapvrrgz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtnhyzdxge.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtnlfgyxaj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gthtkfzjbp.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gtpymsoiqf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gtqphjmkgr.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtbevtqdqb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtnpseuvne.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtimdmisxt.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtczhphzwn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtemzknlgb.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gtnpydizrr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtxvzwuqar.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtidexryuo.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gtdrtjjooc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtekfooedi.html

[R01] shebang 与严格模式
来源：http://dali.smart0.xyz/Article/details/gtnvzbyehu.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gthmzyfuww.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtbioaniqz.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtoakclryr.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gttsznvyjr.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gtugedivpc.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtowaevokq.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gteyrjeiav.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gtolkkjhyn.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtiubrvezc.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtnxeyxgam.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzwpcxvb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtrrrbapnh.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtghctvdhh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtszfhvbpd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtwtsgjaff.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtsgammcgo.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtlacjimmj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtjsfawjty.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtoiurqdsy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtlwridthi.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtvsutjczn.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtmmtqadxl.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtejtrzfxd.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gtbwowgzgq.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gttcatinsj.html

esac
来源：http://dali.zycfv.cn/Article/details/gtvwqqgrsh.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtmbgnulkh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtoldkvqir.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboyhbpvk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtxouuzsrb.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtxtkhefyg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtyvyfylpb.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtgpojgyso.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrimiikoc.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gtcrphudke.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtxeaxresh.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gthtqebwdf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtdatstqkk.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtjsosiwhs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtbigdtbxw.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtxiuqccnp.html

echo "${#arr[@]}"
来源：http://dali.jyoumei.cn/Article/details/gtwcdjwvcw.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtjafsbgor.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtogbsujdq.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaktpchy.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gtqkadoznw.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtqplpzhix.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gturtzfupo.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtpryoaaxn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtyajdzsav.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gttvtakzdz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtbsxhhsjl.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtxwspsdpm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhongyouzk.top/Article/details/gtipejqjvj.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtnzcpwpci.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtwaxtauxm.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtlwahfczh.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtprlmlmoz.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtvfyxvmbc.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtdycejqfb.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gtaxyfdtkv.html


<!-- 参考信息 -->