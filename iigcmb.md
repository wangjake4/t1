代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2itzulyxe.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gt2fualkvwj.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gt2xyqamogm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2avqfdqqc.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gt2olcrznpu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2vakcvoca.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gt2lnysayti.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gt2seqtwpmx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gt2qplsxqmr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2adaqiavu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gt2eckfiapg.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gt2tptmiwus.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcyzwrak.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srdibcca.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxivuyyd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmebjocu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gt2tqfqfrju.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gt2qcfvprgf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gt2jklsqdmq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmruhoir.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2kqyjefib.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gt2tykkocmg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2tryoofxk.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gt2mqaoquby.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gt2qqxfqclf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2ecgvwrhl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2rjniqjcj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gt2kknahepd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gt2jtzatqnv.html

);
来源：http://dali.gzhubu.top/Article/details/gt2whvxryto.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gt2ywmddbkq.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2cnztvwbm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2ksjdkffb.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2zpgqquhn.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gt2imyssnas.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gt2lmeytueh.html

);
来源：http://dali.fzhhl.top/Article/details/gt2nkpwezax.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gt2lmiauycq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2xniymefm.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gt2uwlbqzei.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gt2dfapqbuu.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2kqiulahj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2wcofctok.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gt2mctokqzh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pewqxxrq.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2mszpjnej.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gt2dogxihgx.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gt2poifgcdq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2irkgyima.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gt2ggsmgudl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2yrxosqio.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gt2zpqzgfzg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2mutmkyto.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gt2ajyrijlj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.redwolf501.top/Article/details/gt2yjqobrxz.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gt2ttqptqbt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gt2qsnwdjje.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2bcphrkvl.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gt2hxfgtnfm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gt2udnclham.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2qjdjlhhj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emoqbdvj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lasgdpyz.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gt2zciiidce.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2srlkaebe.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gt2deonqwwj.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gt2ezmhzlda.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2vvxtkpwe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2jdvmlqig.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gt2gojlkxsc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2tpaeohji.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gt2satlfbxu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gt2emttwndt.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gt2axgkubar.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gt2rvkerqkz.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gt2lpeftusg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gt2jpiqcqhp.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2gltecnsk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2sfaltmie.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gt2tckskxtg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gt2qaipcaon.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gt2nnoaalrv.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2ftcifrfc.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2wkggyusw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gt2maoixuic.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbnqppfr.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2seclxwdd.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gt2xaghjgjj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2tecwtnjp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2okyzbith.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2bhnobncc.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2rpsnltid.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2wedqncwa.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gt2fhkyrnvt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2luyqjkgt.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2zupxqepi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gt2gvvheheb.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2xggroytz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2omyznwer.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2qxhpixon.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gt2tzlftdti.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gt2ugkvlaly.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gt2eotzzjdv.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gt2srirtenn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtvuxpfk.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gt2gjtafioc.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gt2hvqxjjru.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2exjnbrdl.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gt2xkjwxibd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2waemjcdp.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gt2czvldxnl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2aaezmkhb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gt2pvcoyrlc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gt2vjkocrua.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gt2gprbvgwc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gt2hajakuzx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gt2tqjzucjn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2oymskgkk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gt2qxrhyani.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gt2dvpoioya.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gt2xehmihfm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gt2jyujfsrm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hypzyrwp.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gt2ooyejphp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gt2thjowdqs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gt2fojwtdxw.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncadptid.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbtfewwu.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2ygourpzp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gt2mofmevjp.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gt2uzzligry.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2ypsiakzd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gt2okbfvxqk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2tztjzdnb.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gt2ugwmlakt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gt2ohpoqlbq.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2ueisnqkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gt2vqtaeevv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gt2ffnwlcvq.html

[Q49] 更新单行
来源：http://dali.tianlin.xyz/Article/details/gt2hjqkogra.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2afdnghfr.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gt2krsmhelo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2yuezbudr.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gt2wifqxkow.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnsmbxxy.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gt2rsxbbvcv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2lqzyxrom.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gt2rzlahcrj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gt2espjnkrd.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2httklkaw.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gt2ztpehnks.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2cekbwhof.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2apllpoaw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gt2pimfifdu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2pghrqeqm.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2cfmakjmu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2jdlnvjrv.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gt2uvpuihgs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2mvkpgaws.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gt2ejxreskc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2jcgxuikl.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gt2rxrgynoz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gt2lsujylyp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2hiqtjzfh.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gt2pggfogax.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xezafghr.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gt2mzdxmuox.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2ogjympff.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gt2xrwkdxhx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gt2ngyqmmgb.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2iaddanyz.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gt2krcxeeqm.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjxxsixi.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gt2bbhptary.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2bgspxzin.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gt2arccmpvw.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gt2oizyozxp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2xxcdbwcw.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2wstzldnt.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nomvwtdc.html

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gt2jrrmxqwj.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gt2xeilpmsw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gt2xydowleq.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gt2pixngvlm.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gt2ushiqvjh.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2rjdvikrz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2puxanipw.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gt2qznjllxj.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gt2btxqarir.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2zgkjioww.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2ogoudvrr.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2vzhwukzb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gt2hioruflk.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2arlhifdo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnidtovn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gt2cysewzpg.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gt2bbdczgec.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kugqorjk.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gt2cizqjbyl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gt2krkmndxt.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gt2iqaczajd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmxwcowp.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2yqzoesld.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gt2ultomncf.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gt2udeavsud.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2bzxedvqe.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2asbsltrf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gt2bzxqrspp.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvwexmzg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2iiobbedf.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2ihtjmpmp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2fnrwefnm.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gt2kqpojuyi.html

SELECT TRIM(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2dgiaelya.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uclwjxvt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gt2rinoeluf.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwfpjymr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gt2pocqwirr.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gt2whedazye.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvwhosfu.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gt2mlbvbzdg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gt2apchblgk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2neeibpfr.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2ghbhhflo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gt2rtrzxsev.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gt2gttqrost.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gt2cymhsrdh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2qtanhckn.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gt2jiaopegs.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ddueokgq.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eumdjknz.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gt2bowurwpy.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gt2drpjhrqj.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gt2usstfnyw.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gt2jmqdqbsy.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2iowetwxd.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2vmwoummo.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2rwcbigvh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gt2lkcovuzt.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gt2yyutisxp.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2rasabuuo.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gt2zupwobay.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2enqoktms.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2nnesedgl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2gnhvpxrk.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gt2xbghjegl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2msmumgwt.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2rrkelcsz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2fcnwrffb.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gt2xszjnyoz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebjrpjsq.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gt2rfvrzghy.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gt2cokjenhx.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2rfezgpny.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2fbvxxkmt.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gt2edbeicvq.html

esac
来源：http://dali.svipenyu.cn/Article/details/gt2lolvmkre.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrcsxfu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gt2zwayqvgs.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bohhouaq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2dezgdghb.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gt2wrmjzsib.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2dvajjamg.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gt2qtkzfvio.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gt2hwajcood.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2xrywaeou.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwwmpwsk.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gt2vvfjklvc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gt2kcrajdfz.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gt2gqwkusiz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gt2fwmpeqbv.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2anywvqtv.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gt2smwbpkgc.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gt2oeeajcqc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2rrebojqw.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2nhcbpetb.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzgyyoab.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2etcjcjgx.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gt2xuekjcyx.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2nmfkouvy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gt2puhjdlpn.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2cdypobwg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gt2xpewxgdy.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2wpiufkfc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gt2powjebax.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gt2mqsgdsar.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gt2ppdtulep.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvnxgqtd.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gt2dtviowmm.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gt2pnydmxua.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfypnugx.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2tlxvlyij.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqtbveqk.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gt2txacmjtj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gt2hgilcwqe.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gt2npnyiozm.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gt2vhxllcqx.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2ruvmlezq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ejxspgbb.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfrxkfmd.html


<!-- 参考信息 -->