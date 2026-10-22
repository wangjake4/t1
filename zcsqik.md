代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtlwxqedft.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaafleolt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngahcbev.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtatfdxgev.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtblyhkrna.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtkcosfbue.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyggvviu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gtdjqzizvc.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtxeglkqwo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtxipwuaut.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtnqnjmyuf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtvcgfxqrj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtqmxqdfjo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtpnbufihd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtsadlapbm.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gttizbwnxm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gthmaauzxv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtsjymvptp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtnbazrylg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtjhjzenxy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtcodpyzwe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtpldwuthe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtnkhnbiaa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtkzpkgfir.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdesfbufv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtqzgqpwag.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttiajeydb.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtfbwwpjyj.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gtrzqvoqnq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gttjepkexo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtxrbxivno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtnnaaseyc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtojpznwuk.html

);
来源：http://dali.cdnleiting.top/Article/details/gtzsnsanbl.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtwhynqcoc.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gtojuruzqh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtyzcvjnna.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnycscyvb.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtsafhngit.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gtxyomyomm.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtnfyepgbm.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtfwxvppdk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtkdcvabhp.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtdfkvjhkp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtkgjmrpbi.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gtmoqtdxqg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtiezjwmns.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtxdmujaac.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gtafxvirej.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtdtvsstes.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtismbstrr.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gtgscmszxu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gthkdzkaqn.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdppfkir.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtauddksuz.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gtzfqxiine.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtygrwdiyu.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtixulvdar.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtkyykeghj.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtereosicj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtcqxgrnsh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtdriyynsg.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gthoowebiv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtobhtugrv.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsbdugxf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtqcpeankp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtjdcoxodv.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtnocdvgyg.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtueshelhu.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhgtdide.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gtpeyzjftf.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtjreatynu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gtheythgkz.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtmfrukmzp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtsdtmomvy.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtcgcsvuvb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtucnqixiw.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtgjvhyida.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtscvjjyav.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtrmzsdnrv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtbmhejesb.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtcyifaboe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gtouwkiynu.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtgrnyyjpb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gtwzcxdtfp.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gtjhrxdlqb.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbithvegp.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtdausyvul.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtteqtpkpz.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtpzruwdhk.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtfyfjsmxh.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gthucvibpa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtreelrqlo.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtbvhvmgka.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtszgafokh.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gthcvnhaxy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfxoywxjd.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gtqtsuaqdc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfkxoupa.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gtfqmjbnlo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtmkakcpgw.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gthdcykjca.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtkatnalih.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtiscqvftr.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtapkmxiyp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtdhzyqxpo.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtseijtrlo.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gtfzqnbuzy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtipfcfpiy.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtrjexejss.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gtzblhnrfy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtcvaqdiac.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtswzxxrna.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtzvprzril.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtojodesoh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gtwiwwyshb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtdyalnnae.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gttgouliho.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtbduhxwth.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gtingffqoq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtxotojdal.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtbgykasqx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtqrgnjxjb.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtbqqrphtd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gtlhcqmeha.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gtyahdlecv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtekaovauc.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtppymvprh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtcqfuhrtv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gtovocdkoo.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtrdexeqye.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtgennecye.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtxzzyuqej.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtxmnuohye.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtqroywalm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtbxbihcqb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtbtfshbnm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtgomxumbm.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtshpkialn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtzfbascmx.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtvxwrkghb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtvtttkzpo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtophwiaae.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gthgoshvmf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtkxpzehhl.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gtfdfcuwwh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtpfausrhj.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtgzqnukfr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtegimlhqo.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtkbmnthjk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtrtsgrgdg.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtitgxglgu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyxegwrz.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtsejckfqy.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasccjjqt.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtwoyoezfm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtstjjrrrp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtvcpfsjmp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtogammisc.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebntiyot.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtioulcdti.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtritfwcft.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtxghxhfni.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gtmhsfduxt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtooylgqbn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtzcooutcz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtmctrttzn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtjnxepkqp.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtlwaqznyu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtheotqkeb.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gtgnqtanls.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gteliscawj.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtdzbzaqne.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtsquefewg.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtedpormuv.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtcrnxuqah.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gtfzkkcyri.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gtyvcujhur.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gtbvfbczhu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtbmjfvqas.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtmujqddhj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtpltznuws.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gtovaypnnp.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtpoczmaeo.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtmucneadr.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtptivqlmi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtqbrpyxgp.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtziobeewy.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtvkbadqxl.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gtjoaepetx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtcoagcsyw.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceaimivn.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtqafxukqi.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtrjnxyirc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtejobuand.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtxeqvaxem.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtbbdqfjhj.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gteowdhavm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtcqoyhaur.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmzqdfkd.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtfypkudlw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gtrymeluvl.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtabjatlkh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtmhqfaogo.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtxwarpyod.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrccuivab.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtjgcavapc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtxguyjhpz.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtrikjkkou.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwryujbgi.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtvykbutxq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtpkuikwdk.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtmdyyyzqw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtegymwosb.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtqwrlzacg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtwrdmrowq.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtfkovfzyz.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtvqagttuj.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtkplpujlx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gtqnilqfds.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtvwcfuywq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtjrrwtlwz.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gtgbhlhnov.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtpvnwyeon.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtxpnrxopb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gtkowpxkkd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gttrynyvbj.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gtpbmtvjgr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtvssialyj.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gtupsfyhhm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacymbbmn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtoatgurej.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfqzzaut.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtftyevhfp.html

[R01] shebang 与严格模式
来源：http://dali.jqgfzy.top/Article/details/gtjmkiatgb.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtbiterdth.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtareucioa.html

[R02] 变量赋值与使用
来源：http://dali.jinghuilouyu.cn/Article/details/gtazrdpxou.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgkstzgh.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtykdtmzng.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwxrglsq.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtzeggxhou.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtvndwgmvc.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtmktlwhlr.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtfnfeknpw.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtenjhsgbd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtrnurvxnj.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtcvtfuqek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gtywtcjxvi.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtsudzxykd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtrfxhabzd.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtaovsdaen.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtnxfqfpax.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtjrwhdyuy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtnmhopeog.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtxbbdfjuj.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtsbvwrkpb.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtaddfohbl.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtqpffshld.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtjqcuhslg.html

esac
来源：http://dali.yongpay.top/Article/details/gtctsviola.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtjgmmacfr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gthghhkihi.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtlfcrjyfd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtyunmtxun.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtodnrasgc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtchoubvjy.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtgjnyplkv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtutmvbcfo.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtjpzqxyda.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtjvkkebur.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgyxwtte.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gttzzuygkd.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtqvkqjxsa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gthterpasw.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gtstgtglfk.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtdpgvracn.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtvergohtv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtcupxapgu.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtpnsetnni.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtjaimcpjn.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtnofygnty.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtjlzzzipk.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gttkqeefpy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtydqjmrdv.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtqyjypfkn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtmyjztzrs.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjjdtfhq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtbdvnjirr.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtzgdorjkm.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtszwdjlxg.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtucwterwj.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gtcsvlnmbr.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtztmygvfv.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtvpsllprj.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gthoggxmjj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkwssswh.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirhoplhw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinphbsgg.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gthomuciah.html


<!-- 参考信息 -->