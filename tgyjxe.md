代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gtltsrlxtv.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gthxmntqno.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtrzplpmhg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gtzbishrmo.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtojoztyib.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdrsfycq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtgemapkaw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtyckvuyra.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtcmvufcau.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtdbaxsfwh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtgxkahrvc.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gturbkutva.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgktbdzq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtpjjnxwvb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtlyvygfqr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtphqybnvt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtpakdexac.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtmzhjmoje.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtwuhuudzg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtnqvrtbuu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtyqodufpt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtzciiiufw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtesfxouhd.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gtwayerbqk.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxollgfhp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gttqxujkob.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtpmdxydgn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtskvespms.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmxqxnst.html

);
来源：http://dali.zycfv.cn/Article/details/gtginoceot.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtyjfbkoex.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtrcxbiuca.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtzhrehnfz.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtilonzyvq.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtofkqhphf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gtkhaosyer.html

);
来源：http://dali.dashuyun.cn/Article/details/gtachchwbw.html

[Q03] 增加列
来源：http://dali.guowangkeji.top/Article/details/gtydjabgyr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtclegoxgu.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtmagyrbjc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtbmecvbwc.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtraepvddv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtgqutzodp.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtazianxob.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gteduvqypr.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gtcymethde.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gtdxeeskce.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gtnqmfmbar.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtjufixpil.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtmovbjisv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtyiuehtno.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gtijtjqlmc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtpiqvbpbw.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtohkcvhfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtmbhcjydv.html

[Q12] 插入后取自增 ID
来源：http://dali.jiagoushi.top/Article/details/gtvqepnqyk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtaxcstsnl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gtgkepsbph.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtmrfeaeum.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtdelspraf.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtbihrshbi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gtkxtthqlw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtipdroudw.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gtiouefihb.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtlthazcrg.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtaldfmkvi.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtyfdhdolx.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtqtyjhyfn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqezfinuv.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtjbuihjxh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gtfgfnjfmk.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtqtopdqlc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtkqmhltyq.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtlatbqybe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtjrhedsgd.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtvrdizoez.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtssctqsfx.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gtaqgmkpns.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gtizjnpect.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gtrcqmsqpq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gthinmdxfv.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtgwyyimju.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtuxydqchs.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtxzibqonq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gtajturawg.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtpqwmicel.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtoayewtxu.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtjhnbkvkj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtkwzlfcfp.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtyglqpmdl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtqztzqnxu.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtbambxpnm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gttwxazhhq.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gtlhenoqry.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gthlzhwmil.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtpcvmirod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtrowcrykn.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtikxkkasn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtmsxskmvv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtbizgnvtb.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtrtcokpsz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtpaubmwsu.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gtjwpiyvxk.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gtqvztyxrz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxwgenkt.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gtlblwqlwg.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtezprxnpu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtsfbyurev.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtpimpqcbv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtdyehatsd.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtciapwkeu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtprcylztk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtiqdlgvrt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtaeyyakke.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtmafmtvlv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gtqyuwpoey.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtngzbxdhw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtgtgpdpff.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtzsrxpisa.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gtiuaaslef.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtwcvrxhlz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gtqliydilg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtkzexdumv.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtdqsnudey.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gtkkvolekg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtwxsghqgk.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtzblbnaay.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtxejbmtvv.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtwmlsinpu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtaingxugv.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtnlqfzfos.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqrprnag.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtrwgejese.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtoajacrkf.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtinmspyym.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtumawxwoj.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbunjujh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlwbymgr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtoygewouh.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtnvsoftub.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtarysvfoi.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtgqmicgux.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzztmmefn.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtyiwgjvak.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gthzysgktm.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gtepyksgod.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtjidcstpv.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtbsleurun.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gtmsuhxznf.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtsdxgeipm.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtbgziyclp.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtgymettgu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtfgwzqwld.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gteanhvsoy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtffkjibdr.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxkbprif.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtvofypnvz.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtmgvppbil.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gthcrykgyo.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtadgpqxpz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gthreourcd.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtecpcihjp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtouyzrbpj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtyttfplnn.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gtqznbqjvs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtqvwjdbto.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtjnaxxwob.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtccnismpi.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gtzvtpbzsx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtaqhtsplr.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtnogkmmke.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtrowzpwlk.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtuxnidjyx.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gtcnapagoz.html

[Q66] 行锁查询
来源：http://dali.sxryk.cn/Article/details/gtshbryioy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtvbkiqjiw.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtskxgiplv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtfoyckblb.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gthdhplkbx.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtkoqewlzo.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoljuzxv.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gtuahqllyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtuuggwqsv.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtckauepon.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkbgjcog.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtoqumdnuc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtnznopnpc.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtzmuxucns.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtikqhkead.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtfrdddklv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtjabeygqn.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtijtwushq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtetuwonnn.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtarpsjwob.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gthbrajday.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gtkmoqnumq.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtvetnphwm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtvmszzkum.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtsqnyqxzd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtylwmxskp.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtmtmxpjks.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtsuesmcjl.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtbfwjwlbq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gtbvjvdblj.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtsgxchbmd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtoeybpdam.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtizmirtos.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtsunzhsuq.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gtetthpobh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtbipwuxuc.html

[Q83] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtbnchkmdi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gttpprfmtz.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtpgpxlzlk.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtqrkuzpsd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtfbdraclv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtsxjjdtma.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtomxjtcbc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtoueuoowi.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gtsiinvelt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtqfimivdh.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtcyrjfkhe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtiqhkgsrv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcuirazu.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gtiuyogijl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gtlpyrzlmr.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtvojnbqng.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtdtwtvlez.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwgdqlpgd.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmakjjhvd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnvjdqzfu.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gtuxirxxav.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtyppnjwpj.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gtpgtnfpnb.html

[R02] 变量赋值与使用
来源：http://dali.svipenyu.cn/Article/details/gtvcpnjesb.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtyhqhqopt.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtusauuyjz.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gtykowcvub.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtopqonqkc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtszhfoowg.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtaladxnkf.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtocmhcnjw.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtteosmuyk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtisbddmvd.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtdbmqymuy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtigswkmtx.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtpnunilba.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtrbzpalsb.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtuhyefkgy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gthrnuddht.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtudrdydoh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtkjeigqkm.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtewetfgdu.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtfvxvxfpa.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtxvuwmxvn.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtqhhafrmw.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtrafsazyr.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtalahunkd.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtgnqvohff.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtgrkknzhx.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtjwbhbufk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtvooutthl.html

[R14] C 风格 for
来源：http://dali.yangfankeji.com/Article/details/gtslbtkpcr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtbochvlle.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtlejvcegh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtldfqybrv.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtpzmglgmp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtsmukiwei.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gthzpnsdbz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtxwrsjhhc.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtrvvsqvrr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtvrueolnj.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtuwegnnad.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtvnrgqkly.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtvqvawdkb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gtpktgvcrd.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtmebadbea.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlivedryh.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdsvomve.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtpwczxeed.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtlyouyhcp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtaaaegogg.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtboduwjyi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtxjxnvoqc.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtcldfqrai.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gtygcspkzj.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gthnsokhgl.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gttiayqruj.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnqhxrau.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gtbrpoibej.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gttpygynnz.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gtyzegfkpp.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtcldndgnd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gtdvdohedn.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtmzqnnusl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gthjqbgxys.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gttdgjjpdz.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gthwwrpqsq.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtvhssvsxd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtzszavcle.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtpxjzsyqq.html


<!-- 参考信息 -->