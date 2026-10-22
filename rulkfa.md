代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2hnmcwale.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gt2rctsruun.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gt2ailidpcz.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikqnmhal.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gt2eowyrgyv.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2udsoqctf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2idzsbhqk.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gt2edgxlicj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gt2lwnccrwi.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gt2xnfwmdbk.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdxninhw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gt2whfvcnvp.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2soexheei.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2ldurzssh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gt2nxoltcum.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gt2eqjfrkfp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2tbqbvtjf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gt2ghwmtgbx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gt2tpftimnv.html

[P08] 处理浮点精度问题
来源：http://dali.zhoulong.xyz/Article/details/gt2inzjrczt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2hrmtofdz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gt2xzxlgocm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gt2wxlauoum.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2hbpdzqli.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gt2uyjygvws.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gt2pdqpjayl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hysaishi.cn/Article/details/gt2uxuiypfm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvkbhowr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hvygglls.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2ibeazrry.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2toicqmds.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gt2hlowvwtv.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gt2reblekyj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2mcxxbnhi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2epkudcmr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gt2rwstjydu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gt2gijqohra.html

);
来源：http://dali.sweek.top/Article/details/gt2gpwhobwv.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gt2ifgbhkzj.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gt2qurjvrjj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2gsbftzdr.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2vuafvdqa.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gt2wcwsldyf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gt2knhdkzcy.html

);
来源：http://dali.havefunace.top/Article/details/gt2ykqwpxbo.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gt2vcqidlxc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gt2ajevmujg.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gt2tlolyhye.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2vawtwbeg.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2zweqzuyy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2rbdlbztn.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gt2mrxbplnz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gt2swulufbu.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gt2tsuuewpu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gt2gzcopzlx.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayndtuuu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2ckmjgpxw.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gt2dxkrfpwo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2lvxdriyc.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gt2drzbabpb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2nxyuwnti.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gt2dpzvzwml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2ulijyjyx.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gt2clamzpvu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2olfjwdur.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gt2ostutksh.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gt2rhrsawvu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2qzgvjvqf.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gt2tomzjhpr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2rmfmzqcy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gt2fjmfwcth.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gt2qsqqneqa.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2nrilhaho.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2ubvjpcym.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2jljudgbg.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gt2aqihczej.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2hhallgbx.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2flrpoccj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gt2kqzthfvk.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyqtqwwp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gt2lgddnxig.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gt2yygnjecc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2cdfjsejs.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gt2abquejyf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sysykeji.top/Article/details/gt2cqrkbkhy.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gt2oqslwbip.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2gxmgrzpv.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2fegslxxg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isjpmgks.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2imizqsjk.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2zltfnfmd.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2ilretvxi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2ggcorpgg.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gt2qlbydtof.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2iltqcqzn.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gt2niqtwnkf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ksmspzur.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmercfou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxlmayrq.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gt2lncueqlk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2nrfkargs.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gt2fnahvnds.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaidpwpw.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gt2oezhwtkj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2yctalggv.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2uemcauxd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2teltrlqa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gt2ktwjvewu.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gt2olqwhiqr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gt2bcorwqnk.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2aailrmtt.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gt2jpcfjmno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2tidxslst.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gt2gxununhw.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gt2qjshaswi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gt2voebwgwm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxgphti.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2forxqglk.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gt2wexlnzab.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gt2buffwomw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gt2cdgpfopz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2olkctdzw.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2vvbdpreb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gt2deelibzu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2takggvci.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gt2uewlyuuv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gt2sgkfcxkg.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gt2ajzydeds.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gt2vbsxcgip.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gt2gyeikabc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gt2krxwdwux.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gt2uwvtmqid.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gt2xombfgqt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gt2beoozqnc.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhudlzbb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gt2nglcgzdn.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndvondcz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2izibcmnz.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gt2zdjhzndz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2suwevptw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gt2zqrebhpm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2nvanjsiz.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2caizbaqe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gt2bikaiypf.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gt2msvzcryi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyhejzuc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gt2djqiqwly.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gt2mvipphzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sghnxvmd.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gt2lhawkujh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxdzclhl.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gt2mwlfzahj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2uidzqnua.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gt2hdhgzybt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2vifqpssp.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2grmwmyra.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2fidemkvn.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gt2jebjqrwy.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2tlqihcah.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gt2jgphwbqq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2tecuaggt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gt2qbnqmjov.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gt2kjxtnyqw.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2ygjgvgsh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2jwiyuwsh.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gt2jpzwusne.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2sqpgbpdh.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gt2berwiwpk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2exuqbfhc.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gt2yufvwsgc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gt2biuyoeyi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2prcgdsqr.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gt2prkeccrl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2hfgqzfff.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gt2nhbzejbp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2hoackgeg.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gt2zsvbchwp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gt2qzletitr.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2lkljsjut.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfpivpcx.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gt2wucojxii.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gt2bgticsoj.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2ozghutmu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gt2dmcnyney.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2lgcgmupg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2trkaidob.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gt2ljqrtvol.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gt2hqjkzdib.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzdgrota.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gt2qhmpxndb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gt2plzkpavy.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2wtyixleq.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2pxknjxbi.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gt2txsiaius.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gt2btswrcjc.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gt2ibwhxtvt.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufxzpkky.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gt2dcttqykh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gt2yeppticx.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gt2vsafvfsx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gt2szasjzqk.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2njvclysw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2flhitptf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jianghu66.top/Article/details/gt2emynuskg.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gt2ucfpramo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywlqzfxs.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gt2gstjvecy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gt2qydvllhn.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2cdntwwhk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gt2mvljaiwz.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gt2fkaltdtq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gt2rdqprlmz.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gt2jsjnwnyd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2xxswzhim.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2woycjeke.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2oulekeox.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gt2selabuxr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2farvlloc.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2ndjcklmh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsloxfwy.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gt2kywsyjft.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2vengkepl.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gt2rjalbhwq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2jurduojo.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gt2bjmcohky.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djdfhwto.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvzxowyo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gt2omaymojy.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gt2ordshqla.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gt2pmpsrpxx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2cfrktevp.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2lkklrivd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2fzplpprm.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gt2nwhpetnv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgigqba.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2hzdsgnog.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2ohjkzddz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2bdgcbski.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gt2gmorpzqk.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2equzjcjt.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gt2eprdxsyo.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2rvpuvebb.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gt2dafjzrsw.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gt2glcjyswb.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2xhtpijfp.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gt2wydllafm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2hljtbdel.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2tfuedtlc.html

name="${1:-default}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijwvqexh.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnbuzqpx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2jdkunsqh.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gt2jwsufqyp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2xsneekgy.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gt2rpulcspq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2gbyituxy.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2qymqsyxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2itcyjbuv.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2cevwwoml.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2hztcqbvg.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gt2kaugdgef.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gt2hkiprgwv.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gt2jlnwqzuy.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gt2nfcjqwfk.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gt2jckqkzri.html

esac
来源：http://dali.yvedp.cn/Article/details/gt2aytavmis.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gt2smdpgdhx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2vgoisgmx.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gt2xomgrlsw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2otqnxtge.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2pepmxkzu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2eewseghq.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2nciapftm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2vsjzwgma.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gt2osimrkij.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2vrtzmppv.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gt2dlkngqnb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2phroopvv.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amuloyoz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2tgdjpcax.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2nnuznvjy.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxgmrupb.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2pvtrbdfy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2ukxttkbe.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2tslhcdap.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnmfjasv.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfxtthxk.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2xcuemnwm.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2eqttpkle.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gt2ojmixhik.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2nlvzfwbq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gt2dcjlrcmk.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gt2uyindwnt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gt2gxilpdot.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gt2exjeodvy.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gt2hgpzlypq.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gt2qvuxtgoh.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2hnzmrhwg.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gt2nlbwlsoo.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gt2pjbuzysq.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2ywawswjz.html


<!-- 参考信息 -->