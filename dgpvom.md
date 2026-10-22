代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gt2gpezffuq.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2hyrvzytv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gt2adihbaip.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2rplbykxc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gt2gscwchrj.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gt2bvlpclau.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gt2grygajbw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gt2lrvaisnv.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gt2jyrfhmyv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2zjbdmmqu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2zbjoyeof.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2gwboypun.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2ztwpbyvr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gt2ftdchrsc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gt2doohmalj.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gt2teiiekvi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yueranfly.top/Article/details/gt2cvpbwfql.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gt2bmljzzcy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gt2wftyncet.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2czhlrxjy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zttsgvop.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwqygtbu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gt2rwblusjy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gt2vdhljxqd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qlybnrtx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2dmpvhhmn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2oitltyaj.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gt2uplotess.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyuzeobz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2qzethxog.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2hmksigcs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gt2iygjkhvc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfawqdti.html

);
来源：http://dali.yonumen.top/Article/details/gt2xodcghzz.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gt2nnizkcls.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gt2lihmugju.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2kcycchpc.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2qcxudnhz.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gt2psmtyatw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpgfalmb.html

);
来源：http://dali.daxiang520.top/Article/details/gt2radmmxln.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gt2nwrumvfs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gt2fbpewoxw.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gt2pldoimko.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gt2amzfepuo.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gt2ittiwdee.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gt2kzsahoul.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2lkpusonk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gt2pmrvnyft.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gt2wmmrjrht.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gt2hkdfhude.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2vjwxyfbq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uawynnob.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2gaeqhanr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2empyghgs.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gt2qrifjbsj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxaktssq.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2xjusjofa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgzfhuia.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdugvszn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gt2dsepwyfx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gt2cdcslwdb.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gt2grvqbnvd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2dywgqmxh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhongyouzk.top/Article/details/gt2zzwtweej.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hezgcixg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gt2hwmesaal.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2xkczugzi.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gt2dvgixaxe.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2jokosuxm.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2xglyxtbt.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gt2oowbwuxc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yasrcbgn.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2ptzozaio.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gt2wpbzaetc.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gt2formeaea.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gt2qheyhrlq.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gt2ucbvsnie.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gt2kulieufu.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2oktqctgs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gt2cgxsnkss.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gt2qjyrychj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gt2klkwutbp.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gt2bysjlhof.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2lyqnmtat.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gt2lbcebxzt.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2zejeissi.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gt2fmebvqfm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gt2cwbflxst.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2iodusrtt.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2ysimnxry.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2pgzhshxj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2bwfwagqq.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwovtfqm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2sbasccsk.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gt2euhwaepf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2qoprvgmw.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gt2rnpgvalf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2eebelstc.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2jafydeun.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gt2aikdbhvi.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2ludjoijv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2annprlvh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gt2hjmgemin.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gt2cbqewanq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubqkmzgt.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsrheyeu.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gt2fydbzsok.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gt2byfawfmi.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2yepeyqtw.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gt2heostqcb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2twburwoa.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gt2hakkanan.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2nsvyntbm.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gt2pxrzkzis.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2fljrxxsw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gt2gxuheocm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2bzipikpg.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258.top/Article/details/gt2phfywabu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gt2ljmoisma.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zibybrxf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gt2thkgwmbx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxyzfhct.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gt2yvarwrno.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2nkxcmrny.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gt2eqjombvl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2eduaxpyf.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2chnrpljh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gt2uukfikbb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gt2isnzubuq.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsamgwqj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2irikbbzo.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2zghfucco.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gt2fyjasnbi.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2eluhdtxl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gt2uaezjyca.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gt2odnepsvl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2edfpgwnp.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gt2xkpqsuzn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2qswtqwlt.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gt2cszcgyvj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gt2xvoysxtg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gt2dpeuokxb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2elcsekka.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2zukyasjw.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gt2fcjhkgrj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggtftyiu.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wghndhxp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gt2fkansjvs.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gt2poaedtcg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2ecphypkt.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gt2itreucxi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gt2gsigvcnb.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gt2xhaammoq.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2gmagvnsh.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2qtlgytwe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2tnvhxacj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvystmqi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2eyzcxwvx.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2oesbqkkh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2auahsiex.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gt2ccvypgmd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2flyzsqbe.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gt2bbghgpdd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxwmxsdh.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gt2phvfjmyx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gt2jelaybqv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcwdkbxx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzcbkwn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2ipuurzyf.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gt2gsbywikm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2psuppwgy.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gt2gshjnihu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gt2aiunegec.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2qzgghptd.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gt2sgheejor.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gt2jagrmwuc.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gt2swboigzf.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gt2zllnmltd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gt2vukxwdht.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gt2bkzemapl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gt2pwphykql.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gt2hodyktes.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2kkutxsth.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gt2tcdolnji.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyqdjkq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gt2xyjtyepu.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2hbqwslnl.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsqwwkpe.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gt2ualveojq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2wwfqyyre.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gt2tpsaohmk.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2invmeinx.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gt2ezoidbpi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gt2aykivala.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijzrnnhr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2pshijjdr.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2vmopokyq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2yqvnyhha.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgkjzkn.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gt2nmnepzix.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gt2svobnqij.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2bogqlykz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gt2mbofqxps.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gt2qkterdvo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2cttehnsg.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2ptuvfiry.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gt2qxslpmek.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2juabvdvz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oepnxuys.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2jbpmlhdt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2piwgcusm.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2mztcbrqb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2vjoaimnb.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2gypbfjlu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2bmiqkuap.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gt2fwibjnrx.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqrpjsjj.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gt2lyozajqt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gt2icadfnar.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gt2nntzhwcr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gt2enalkgoj.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gt2yroydles.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gt2pawljbdn.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuujnuji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gt2moozjhnx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xoltiueh.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gt2czbcsrit.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2vlcgwibr.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gt2wenywsgk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gt2bwbmxidn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2phaaqpml.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxgzycal.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vdlbujqr.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2khxpfhto.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2iuonzsvx.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gt2ykmawxzl.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gt2fphsokqu.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gt2efnmxgpa.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukveoyxb.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gt2opavlvsp.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gt2eljigyok.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gt2wdpnjkpk.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2nmqbfxos.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2axqzbgue.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gt2qvukbnjh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czvkwvyb.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2bfyaclyg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gt2yftzkynq.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drbylems.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwnhqomf.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2yvzldwir.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gt2pqykkenh.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2zwumkxui.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2zubkxaxp.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gt2xhghjvco.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2wgzquath.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2dpvklhom.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2mtwzvcyz.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eiqydgmf.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gt2kauqphhw.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkqjlbfx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gt2jsivtdco.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2iobvngdp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gt2frtaubmy.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gt2vrmmmyvx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2pxuencri.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2ctqdbyew.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gt2jzmuhbbp.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gt2dbirvlvl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gt2wgdlhmzm.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gt2nsoszplo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2bngklvry.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gt2uciselza.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2igooocwq.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2igcsjfop.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzurdzuw.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gt2oexbljaz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkklpdej.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2pdxfypnq.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gt2sorkffsm.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2qxthjhcu.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gt2edyauwwc.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2cgmxohcw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2szxxczig.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2izhwskhd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbplmpdx.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gt2rpshhmrq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gt2jcooxojj.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gt2cywvjuza.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2rbpdqbuj.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gt2tsgnaiwz.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gt2atgkavbu.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gt2kvhulmwp.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gt2yqwixrdd.html

[R29] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gt2xxfluwov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gt2iybthsbo.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gt2uaviffem.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gt2ejflygpw.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkepepfq.html


<!-- 参考信息 -->