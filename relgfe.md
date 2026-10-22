代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gt2lrqxfpef.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gt2wiblwlgo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2dwizfhdc.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gt2nvbeuzjd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gt2qpcoqeni.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gt2loewnrrr.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gt2gwnjsuff.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gt2xlwhoyin.html

PHP:  // 手写时间戳比较
来源：http://dali.snrcjt.cn/Article/details/gt2sckbiwtc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2arcgbdbb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2shupbywb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxfovpbf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gt2ujifswar.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2xdljqdwo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gt2nxmljwxy.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gt2gzqjgaid.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gt2ylglarrc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gt2pmemlmxx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gt2ohnvglew.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpriselz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gt2hvaeqcwl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gt2oesogjii.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ownfvsgw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2xaghvkdu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixmwjwbm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gt2dfbebpot.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2owaotrdh.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gt2brfcpmko.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyzspihj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjtgpeyh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2byjzhqze.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gt2zhjrfjvj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gt2agqjsxqp.html

);
来源：http://dali.sweek.top/Article/details/gt2piisxfrq.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gt2csmixgug.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gt2iprxmqyd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2dsjgbtug.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2lpcfsyla.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gt2szjbhwph.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2megksktw.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2pysdcapy.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gt2evokngih.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2bvlodhuv.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gt2xzoxqyhp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nqbfzrws.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2vwvkaghy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gt2tzofsgtt.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gt2wdvplmzz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2dnsuohax.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gt2kbcnnwmo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2dtlkddpm.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gt2dehonozx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2eltwevrg.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gt2sjvtucwk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2nqmtwgyz.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2smeplymk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2ftdowfgj.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emvpwpss.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2gfalrvgm.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gt2uozcoqln.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2pceumakr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gt2nystxfcm.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2clristsr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2pqnohzxr.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gt2adoppimt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2gzodtqxq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2ilbvtsje.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gt2jztyispu.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tldbojdv.html

[Q16] 查询指定列
来源：http://dali.c1oappe.top/Article/details/gt2anuzhfvv.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2bapnthjn.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gt2iaiesgui.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2iiplflfo.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gt2ztyklawp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gt2oxmijdrg.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gt2qwocwdwm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gt2bzecuyto.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gt2quiuwxlz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gt2koygzpwp.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gt2kgauygem.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gt2pjitsfcw.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gt2ercozgoh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gt2ezoucabi.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gt2isowqrmr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gt2oegomnmc.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2jzljohrx.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2kncbisbo.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2aadmulzr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gt2gonmcwrh.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gt2draxjefd.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2zghdeacd.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2oxezkiyp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xomfypwm.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gt2wmvbuyjr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2qrncqmwu.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2yauuwhum.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2gwqqmxvi.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gt2jnbpermi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dctipoqw.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gt2kztcyvdz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gt2uetvduju.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2fovgotfu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2maamudsr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gt2buljxozu.html

[Q33] 多列分组
来源：http://dali.fzhhl.top/Article/details/gt2mvdayrdf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2hkizdcep.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gt2jidsatyx.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gt2xarhugep.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gt2pxkxskep.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgvhwikp.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gt2uyuleceo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2ubofxiby.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gt2pgryhuiu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2myckoaau.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtssrtdv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gt2egyatrru.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gt2cnjpngaf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gt2zoauxkbp.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2llvzhtaf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gt2bvpynfko.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gt2lfcalsvt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gt2qpjpyocr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gt2bvjmztqy.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gt2hwdsfkau.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2afiyymxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gt2ejpsxisp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gt2xaogowpo.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gt2rffxjqwe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gt2ayvmdwdq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2edybemqp.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbfqltsn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2leiausrh.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2fsrttqps.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gt2qcluguqx.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gt2ojmsrqzu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2tjpumqan.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gt2lilgwfsb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2nlqxpvmw.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gt2neyffpes.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2csqmyujb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ympvnsmm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2olhfvswx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xavgkcgu.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gt2jhbeovnq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2sxtwyubc.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gt2nrzrkvmu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2kgowecvx.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gt2mloudcjc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2qjbawexm.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gt2ihghctap.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2czbhjgte.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2fvqlqaou.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2aomwdpok.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2trncvqcn.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gt2nvwcjidp.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gt2fndarjqv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2padkgykp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gt2cpajmjku.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2mzduakqh.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjyumqxk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xisfdjvs.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2ljrwbekz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2gmwobsbr.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gt2jjwawdob.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2mlgayrnu.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gt2wjdsldgu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gt2udhjwdpw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2xqvmmxzb.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gt2awdmrnsq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2jbhuiqzq.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gt2cvvyvclv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2twmlmidd.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gt2cagklohc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gt2mabzcalw.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuoryflm.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gt2hxalsrxx.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2lesbwurr.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gt2revvvpvs.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2zztkojgk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gt2glttnzfw.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gt2rylkbgon.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gt2buonqyrk.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gt2bpygxxee.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gt2jvsybshj.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2rphoitvc.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gt2csgsaiuo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gt2yzrdfzlz.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gt2qjtckuzw.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2nzzdgthi.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gt2blnyoaxd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gt2zlhzijgg.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gt2rzfofyfx.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ywvscgiz.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gt2oxfdvqdr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2bfxrgxup.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gt2jpmjywin.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ierogigg.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfqagvfn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2agebqguz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgrnsdlx.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2oidrwcdq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gt2optjnzgg.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gt2igurealo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gt2lilamurq.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2xeeegyia.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gt2kqobzhrq.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2avnzlicv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gt2eptuukgi.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gt2mekgiouq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2isrceizf.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2hfgvpepc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2xeqxaptb.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gt2guqoqxzm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2bmzqtuua.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhzjpknc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2aeuwlisj.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gt2kinwxqho.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ijqcmxgv.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gt2yvhfhgvi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gt2sbsjpzmj.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2edjvyvma.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gt2jlqrzwqs.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gt2ejmpmjca.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2foazvzmc.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2mkcbbfyo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gt2aqzpnzpq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2gnyyibfp.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gt2xjzdysaw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2yjzdjuqw.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gt2tsbzfvnk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmwjwsmz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtsigcqj.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2bazdrwpi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vjceucyw.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsqmmmut.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gt2qtdiwpqm.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2sbflurru.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2wufscnck.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gt2xdgbmazw.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gt2afyccujv.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gt2qqrusgwq.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gt2ovznsbrw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gt2zzestfju.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gt2zuvziybs.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olcloskd.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsszmcem.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gt2zfmmnoqt.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2eqtzmqqa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2wsghhykx.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gt2fenestpr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2iawjqftp.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2waizltnt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2xejbssoc.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtacjjrq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2dvgwbsdq.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2aexqgnnh.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrfpeadd.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2hsphmbaf.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqrbdyss.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gt2qhmhlput.html

esac
来源：http://dali.ybcxt.top/Article/details/gt2toxntigg.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gt2scghtdon.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gt2iduzpgid.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ournykyv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2fetvkyvj.html

[R14] C 风格 for
来源：http://dali.svipenyu.cn/Article/details/gt2kattbnaf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2hwouwrvb.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2vslqqgng.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gt2asfqglwa.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gt2uqvykjzd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2mtluappi.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2ddtkmpve.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gt2bfyuosgq.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdfrghqh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2bntppbxi.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjxfnnug.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gt2mxixzoem.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gt2rwesacxw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2fuwigtfe.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2pkypkwis.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gt2gomgjdru.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2ugmcsthm.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gt2hyiwzjbb.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2qeofhjwx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gt2xfsqvghu.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2jqvkdjed.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eigqoidt.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gt2edkepcqw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfmfttak.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gt2vqzjlzwg.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2jmcvvomk.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gt2svncauly.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2xwpmxcpm.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gt2snahgndv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258888.top/Article/details/gt2vtkwvxtj.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2aiugnrkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2vronvmdm.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsbltaof.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gt2abxfgkzs.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gt2vsrllndk.html


<!-- 参考信息 -->