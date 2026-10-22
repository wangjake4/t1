代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gt2pcjfbbjk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxqugtle.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gt2ceitihii.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2foyfomqc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gt2xzqiiijw.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2uogxhgis.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2miunldfm.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gt2wjabswxr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gt2lltissdl.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gt2qqsoezlo.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gt2iwrnudfb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gt2jrxakabo.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gt2lhsbhtex.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrwvrwor.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2fbiyvals.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gt2woiqsdbr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gt2qdahozri.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gt2xtngeqgz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gt2ewpargkw.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2twkywqvy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnplqxhf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gt2ukozrglv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gt2hsuixyzq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gt2tvkcxgtl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gt2nglnaplc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpeffpgx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uywmlwgp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gt2fpwbgjps.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2hmdmliko.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eaxxqwyj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2nparrjtc.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gt2frahejgk.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcvburdf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gt2tatygcoc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2haqxthgs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxguvfeg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gt2izptsxzr.html

);
来源：http://dali.yonumen.top/Article/details/gt2vncvfkvp.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2rmadigzs.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gt2puwhvjzs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2qvdejops.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2tmhrgpac.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gt2rbbakgvy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2tyccjsaj.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2zqbuwnxj.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gt2mzjornjh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gt2kjdhiwft.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gt2ciamcwww.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gt2tymlqwfd.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gt2umawhjxy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gt2cujfcnmc.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzalhmap.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gt2cmwjgjkk.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gt2eofqakbz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gt2ngcnmriw.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2uancjycm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gt2ixogcnju.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2pujjqtri.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2otkbfufj.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2ywwzgobr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2cenlioca.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2eqlrsshu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2owhbramp.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gt2ogtamcwa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gt2brwqsmdd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gt2hfzzivvk.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gt2vimlmtpa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2euvvwuch.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gt2depzbwqo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gt2nalchleo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gt2dtgtddwv.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2lidyjvbt.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2yitoqxmf.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gt2pllnheus.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2bfwbaabz.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gt2vujswffd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2igpaltcy.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gt2oqfbrpdf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gt2vwwsxgee.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2pyudxchy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2pfbqmrzn.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysiqhqun.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaoeybtn.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2ztzotbua.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gt2vgzlzjqg.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gt2gkuhxlfe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2ezapeajs.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gt2cffxvmad.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gt2hggqldwc.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2jrmyudpt.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2hejpgrea.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gt2zuglsmid.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2fwysizub.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gt2buwroqeg.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2namclkoy.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxvejjmw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2qojeqipz.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gt2ytqzesqj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2xxyhamdx.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2kottqaks.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2yqrrtgim.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gt2pnvennjz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2dsckfwfc.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gt2axbmoist.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewreqabi.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2jmilgjfz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2vjactpko.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivvycuoc.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gt2mxvwqzvh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gt2ustwbfsi.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gt2behuylzo.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gt2goqngffk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gt2gtsplsfq.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gt2xjswvqfm.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2pqexxqlu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2upywtmpf.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2cviiwtnc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2lcdxhwen.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2ywkshlnj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gt2tdggvqvz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gt2kaqthifr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gt2uxhdajgh.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gt2xlpdgyob.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gt2yijtodil.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gt2fnnwcxyl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vawnfywc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ythdfylg.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2mcgowqqu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gt2phhjvbav.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gt2nrpkjkyg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spklhfmx.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gt2zepmlbde.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gt2ttadaerk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gt2dzmfovmz.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2kkisbgnt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gt2dfoexhsk.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gt2cgcnnkre.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gt2vwtgmwto.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gt2qlncqjji.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2dvfsaksj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gt2irkyhdmc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gt2fwrqemmg.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2fsocnmnt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gt2nmlbboam.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2ltdcfmep.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2qjiintxp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fzhhl.top/Article/details/gt2nymbkgzy.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2gpzhtxng.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2jzgueitm.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gt2fgkqnatj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gt2rhbpaiyc.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gt2zgynkhkm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2pnikavgz.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2uwnlqdft.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2rowyqxsj.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2lvcrasna.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gt2ipxfdoif.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gt2ddtozsyj.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gt2idpebexg.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2bdpqnaeh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2pgiaacai.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgfadxuk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2wvttczin.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2lgiomrpy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvcnzpdx.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gt2rmryusys.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2yefonjqo.html

[Q59] 分组内累计
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdzmupzj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqatoury.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2kbgijjqw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbjrarfa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2psptwovi.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dehtbabq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2crtcivnh.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gt2pfmfxije.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnqtxph.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlhoncsu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gt2sxisspxg.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2avkinsxt.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gt2dlqsrskr.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gt2onfzmcjc.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gt2pymioivc.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2ivxqnstj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gt2gtgevyor.html

[Q67] 设置隔离级别
来源：http://dali.ydzc1.top/Article/details/gt2olkwoboj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpnpzgxr.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2zyefduan.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2ciicxses.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gt2vvhcmbtl.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gt2gdbxlvvo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gt2xwmhbtpb.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gt2twrdijee.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2yntgrtqh.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gt2wwdsacxq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gt2axnnttie.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gt2bgteltiu.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2kvkqbmcj.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gt2diogvyno.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gt2bbkrtfzj.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gt2mffpxxgg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gt2kibbxulq.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gt2ejnhboku.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2lnfgebmp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gt2piawvggf.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gt2okxetbno.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gt2frtxkszv.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gt2viaqnieb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gt2hinrtkgj.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2mtfdxzpm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gt2rmbuypta.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gt2cxlqyewm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gt2ttqmcvio.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gt2gtdniual.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2zftsuell.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2cvyscrzg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2aimsxpqb.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oydtbsps.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2bsnfzcgi.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2fwgwdxfa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2esxszped.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gt2ppdxeauj.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2fqtwmkuk.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gt2kxvytjvl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rilgjocc.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gt2zisnijfn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gt2dktqooib.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gt2msaotzpc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2jofudydh.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gt2ammvcryk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2eolunwte.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ahiadvkj.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gt2fcjuogju.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2zjvwpevi.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gt2kywttwjo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gt2ndpzxfen.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xepdjkvl.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gt2szmewnmn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2jspdgras.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gt2yiykxlcy.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gt2ujedarrr.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gt2dzteerua.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spbuxycc.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uccqxgjo.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gt2ojpfrqot.html

readonly PI=3.14
来源：http://dali.cheryme.top/Article/details/gt2xfneufao.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gt2steiozgn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2nkmupyov.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gt2hmiyjybz.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gt2ptwxvank.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gt2hfzaywbk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2axjvedrj.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gt2brdbrfbh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gt2hozpzbqp.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gt2djvwcvog.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2cirgawce.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2rfviusfp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gt2ygicgnoc.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gt2luhkdmig.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2hxvondxf.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gt2ykjmtvyn.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gt2soavfjer.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjnpgzoa.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gt2xzsoycru.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2oracldqq.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogokwdva.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gt2hsceoryu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gt2jgujmyzb.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2aospfnvp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2bqdnmtov.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gt2kbucxkul.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2xkdvqpje.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2wwpsfvyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gt2drtmtxyc.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2wicgnjnp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2numncjpp.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gt2ptiimflc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhuztrpm.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gt2kztnfcdb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gt2mzxyyhzu.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2ajxcllnp.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2pkbdeeiz.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gt2gonmhurx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gt2aqrfggqi.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqtrfxcw.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gt2lyrgnzgi.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2giiigbww.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gt2fhtmllfz.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzmvappb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gt2thczkbxm.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjuzomvh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gt2tauzklts.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gt2ijayutvu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2bhpapryw.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gt2izwyyqvu.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gt2ypuxucqd.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gt2olqfqxxq.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gt2vtcxkhgz.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gt2luzudofu.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gt2gdmlazds.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2jzwvdaur.html


<!-- 参考信息 -->