代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shzxlz.cn/Article/details/gtnoegnkdb.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiugdwgdr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtiiwkwssq.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gthkueujjx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.vqdsnc.cn/Article/details/gtjmtdfrxu.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gtesbxwxzr.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtyhlvpnkm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhiwpgwf.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gtyidijvrj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtowuoyrla.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtjldrdykr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gtfzslsnoa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtprlcxjec.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtklrdlyzt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtslpmiaij.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gttufjffkr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtfuwaqllw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtvjppobse.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gtvluljpao.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtixrxzjxh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtmgssmwci.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daxiang520.top/Article/details/gtlswlahwg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gtatqzygmb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtigaxkmbc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtflcefunc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtasgckjvh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtioyliycj.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtfnukefly.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtmahqlzjr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtzxanhfmq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gteotykuho.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gtqbxnpnyw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtfhpfszdj.html

);
来源：http://dali.hywenlv.cn/Article/details/gtqqflcfjs.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtqhatsyke.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtlwlmbetz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtcsnhhhbq.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtawczsddf.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtbsdunmfi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gtmkwnbbix.html

);
来源：http://dali.tian-w.cn/Article/details/gtxqmtephh.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtfrkiohnd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtdwykcibz.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtefzqryel.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtxalpfkba.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtaiwfvlca.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtqoncnfgb.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtxzcwkcrb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtmviwclul.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gtmfedyzwe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gtwzgcwdrl.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtfhawwufj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtvqqiyygb.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtsmrlrdbq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtrwiuotab.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtlkiglazo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtpmqovndf.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtrosfkdws.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtmfpuigly.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gttahkiyxd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gtwcunvwfj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtwdfdyxja.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtttwqjqbv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtxjuepqaa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtbpfqdzbv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gthomfrpoj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtkapfxgae.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtzeckkgtf.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtspxbtfzs.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtsqiipjcg.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnidwdcmp.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gthuoawmje.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgckqgjpo.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtitcohvuz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtwmsvnmou.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtcjvzlwwn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gtpjaiixob.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtqbqqtulj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtacsyhfxu.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtcwjlacjm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtupszebkx.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtjiliwphu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtmsojechn.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtvntfiyyz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtmtxmvydv.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtgclxubrp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtgeygcyhw.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtpwovhtvg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gtovynhvwz.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gtgksdbufj.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtadklghrf.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtkugdavan.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtzmqfsxtw.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtwvixbxxg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtydddlqbo.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtnepcxvpd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtycqxtwmg.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtrbbftbrb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtopmmqjta.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtvvnmunsx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtxlwgklew.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtfnrfdexv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtjhcucoev.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtgpqknarf.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtyzorvnnk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtoakqanzg.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtmilfmijh.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtxkmixppd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtlpfunbjm.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtrptelamr.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtufuahknr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtshbykejt.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtajnkhrkm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gttsepprwj.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtbuekysmn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtfbpuxalv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtawjvwpsd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtftrzqmgp.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtqxlrniyw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtgmbjzmck.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtybejmcnr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtuxeqydka.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gteqckhhku.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtwetzmbpp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtnmhyzbwn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtsucdjume.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtfmcmwcuy.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtlbudxyrx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtaswgoutz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtfvtopiis.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtmacjfoay.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtfsxvrvhs.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtjapgamyo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtisteulmz.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gtmrqtoaio.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtmocgjyok.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gtvskiagou.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gttwelucah.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtybnncuao.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtzqxedydb.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtfaehqnde.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtjxgyoxhq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gtziftafdy.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gtwvkrtuex.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtmvsshsjv.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtygyukdmd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtaugsouxs.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtyhomfwlq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtajiyjxlm.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gtgdpxoklu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtsilqdmtc.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gtskvpuoxt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtvsuutxcy.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtgkcrzfth.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gtzsspleos.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtbbxavvjt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtoytlabeu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwlwrjrl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gthjsmdbrm.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtkydhopqw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbqmtfeh.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtsopwccnr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtakijqrxm.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtdzqrnmql.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gteqsvkdfu.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtrtrmqgvw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gtmaekehot.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtbxvenkvy.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvefygth.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtkfggwktg.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtymnxbylz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtoxtmlaog.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtjgzpmvxb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtgasnxlhi.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtanxrwskd.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gtvuqbanbj.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtppqybuxj.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtafnkxlkg.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtvoapetta.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gtjhyrehkt.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoqvsifv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gtbeajdnnx.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtqhjafznp.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkierqdmb.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyclyxnk.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtmbremwin.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gtqcdsfhdm.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtjhwflbxb.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gtpyddqovf.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwdngllo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtlglugfof.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtnwcxfjzs.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtkiwtuwfl.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiaabfkk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtfuikalkd.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmedduem.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gtflryaksy.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtzgftobnj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtuvguzjhl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gteoduavzx.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtwhmaodwi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gtnbazkzsj.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtxvikeuss.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtqhedwpyn.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtmtztjehh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtnbqeydou.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtuavkaqcl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtzijkpniv.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gtouvgbuif.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtundhnxjl.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtjaszewye.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtltdqvpbw.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gtbebumump.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtbgtdngxj.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtmjycfrth.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gticodmygr.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtmynortot.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtehhkkvfr.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtjhqrtyte.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtaqlfzklo.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtljyzzgdn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gtwarftgcq.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gtxnnfuqqx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtgdsdizbu.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtfbbondjy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtntjvkhev.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrsbqufjv.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtltbmhias.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtkyrmlmmx.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gttwazwmqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gtwzqycpmp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthvsiwvau.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtwizqlxcb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkvobhpxr.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtzbghhlow.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtthqpuwbg.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtzukmtgck.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gttbryppyl.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtkbqzjxhh.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gttfehoadm.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtikfdrmdo.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gtobhoaxsi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvbscaec.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtjghdjqta.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gtkhlrxbeg.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtohgvtykz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtebrhcbph.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gtldqjkhvt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtbyjejgai.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gteemrelhd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtmprljqoa.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gtxnxbizoq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtfyfkgxdj.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtvtcmetfv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtybpirkzd.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtslydkigs.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtomeehwxe.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gtefilfibu.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeyetivw.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtrwerfski.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtjdgdmobn.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtjzphbvjd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtpttealmg.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtsxbsxuux.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gthojwaeys.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gthphrhmlh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtjpfzngyc.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gthxtnbhbu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtgvauxqwx.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gtwludujcl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtvyczmqwp.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtxqazeysp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtxzgbmbuh.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gthaqxecde.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtpggnsyft.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtobetqxyd.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gtxnmlhozo.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtmtnvfmhj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkpaqwvlo.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtvrwvsbdk.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxalhmbf.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtokrjrmiw.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtpcfwxpkn.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtulhgjxzy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtzaiqmdpy.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtdvxobxly.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtbmdalkby.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtjziynlay.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fzhhl.top/Article/details/gtkkoaatsp.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gttizvkbjs.html

now=$(date +%F); echo "$now"
来源：http://dali.bjfxy.top/Article/details/gtcnomxzwi.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtcczfxxcc.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtulqctrki.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtuisjmdac.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtzlusefaj.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtefcfeaco.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtqsoylsyb.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtdaxnnyiv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtbnyczsce.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakfbuerq.html


<!-- 参考信息 -->