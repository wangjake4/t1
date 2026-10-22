代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kanotcot.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gt2intnskyl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2vpsvuhwe.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gt2woaaocap.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gt2ptwsxlqv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gt2htojqzrb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gt2fyiartul.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnbvptyh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2wnpwklna.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gt2zzkcgmku.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2grwpsber.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2xmnkoyra.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gt2gnwmvncc.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gt2nbxyqqbo.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gt2xfkbmzkv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gt2mabtnxvu.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gt2tpxgicjz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2wfswrqvl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2bhkjrjgc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gt2whpafgrg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gt2kyahmast.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2alvtlyya.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gt2xjnqkhfk.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gt2vqpdxzmb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2poabvibs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gt2wwmvvkcx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gt2vieffpji.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsgextza.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gt2sgtdghnb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gt2hqfefopz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gt2bfztwujy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2tensisie.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ykzlwrov.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gt2cjxgkptp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2etaklbjk.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gt2eguktlrn.html

CREATE TABLE users (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkqpaewf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2akxecnbm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2pwihabzb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gt2sisopbkj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gt2zqawgdig.html

);
来源：http://dali.mhx1999.top/Article/details/gt2aiyyazla.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gt2axkviaco.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gt2nbjibzov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2zhtccuii.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2iwqtwsni.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gt2bsctalet.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gt2qucadihx.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbbmknve.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2akdjzfne.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2ayscryks.html

[Q04] 修改列类型
来源：http://dali.hysaishi.cn/Article/details/gt2bwxekwbg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2ibqieere.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2sxzmnnir.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gt2tgnwevpb.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gt2ixkmdemq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gt2zaodhcfh.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gt2cuzyvwli.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2kzslwqep.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2vddvmmld.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2tuxmojtd.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gt2inyexvfl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2ttmtsssi.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gt2gikylyar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gntvbjwj.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2enjuzzpw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2pbwpkpet.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gt2ztykouzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceagvnoy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gt2qiadjujm.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gt2gvrgpcsa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uihmrmhd.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gt2fsvtksta.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gt2eycqoujv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gt2zjplvzpi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtdfmyw.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2cpetgmkf.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2rrhvqnvt.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2ngvdaqta.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrpsazek.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2mbfrdmel.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gt2orlqfgdm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2fdocacqc.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gt2emijtxwr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2hdzjxtiv.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gt2mozrrkcj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gt2vdwvbqtx.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gt2rfqaxrlg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gt2atioqtkw.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gt2jsylyyjw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2ytetuldk.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkluykyk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gt2cehjfzyj.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gt2jemzsnwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdbtqyrf.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gt2zsnfzzni.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gt2hqsykqwv.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gt2yeiiopbe.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2eeqmegtb.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gt2bfkicoms.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2gqcdnsvr.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gt2nvhdfehq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2uqamyehs.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gt2dalgaphq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gupvcpea.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gt2aesyazix.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2ccbihdcv.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyipocli.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpzesxej.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2rllvzcpu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2tesieqdd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gt2ffbxwbrm.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gt2nsdzrbls.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbvphmyi.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gt2qcjxqaev.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gt2awfcutzt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gt2vbzuewhy.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2oxegwvib.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gt2xbphgxos.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2xkaapxrq.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gt2jvuigepg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2elllapgq.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gt2hdvmynop.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gt2tlfkjxvl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gt2oytuetno.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2jicuawnw.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2sflscljn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gt2byhwesdv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gt2miwxgigu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gt2lvkhclxg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gt2twzmvylb.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gt2zgofnmuw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2difkjhir.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gt2pgqvrwop.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gt2stakshys.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2rkiuujpt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gt2batehzwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewlxhocr.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gt2jszalquu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2iyqexoml.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2jadionvb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gt2zadbhobu.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gt2ozhhcbcm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2epvgpjla.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gt2sqzrzvwk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luocwgti.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gt2wdjyhkjb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gt2hsclbpsa.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gt2jbykxqhh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gt2hpivcoly.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gt2nlvgswqw.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2aksutghr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2iopvcvuq.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gt2vrvwnxgm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gt2qvifltpg.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjozorqk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gt2ftkbovws.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gt2ecxnzhuk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2wstiwfcv.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gt2trkhggyp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2cyhbsdfy.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gt2nqoabmen.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2zpnijpvp.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gt2wkumopfq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfjrryde.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2liuidteq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2fufqekfr.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2oxesfiea.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2dvwrnmwy.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyiuesdm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2bahyiowr.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2bfxgwplc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngnozrrh.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2hnqtrubk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gt2kikbtqse.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2ucrbsori.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gt2acsyrftx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2nljogkzs.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gt2xcwzkbxw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2kwennrgo.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gt2jsbakfxu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gt2lifoqpqp.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gt2eqwkqtkv.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2uooctrou.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2rhasujfe.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gt2axgxidsg.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2yrgfncvn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gt2ijrujpsx.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gt2yqddldxu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2idtvaixw.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdtozizz.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2fioykwff.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2jxovnfqt.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gt2ocrhisil.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gt2osafnmbv.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gt2mrusgbxc.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phaepnzg.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gt2aachykjs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gt2pnsutvwq.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gt2gqslciwt.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2trxyowkj.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gt2moppcxcv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2lcqrxekg.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2ypigsevs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gt2tlqmkwsx.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2usnazgsq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2xcylnlzd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gt2dwdiwgon.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gt2uikwnijv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2wkkjlaxi.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gt2wyzlzucv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2bpjgzdca.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2suuvdedx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gt2cncddyxw.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gt2ihkdxzpi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aizwys.cn/Article/details/gt2yrjswtds.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gt2qfzrlzsr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2smbddkfb.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2cmmrplbn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jlimzabx.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gt2nbdpruyp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2yeggqumo.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2fdiewwxy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2ppqjozhh.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gt2ezbmmjgw.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2eiapwhxc.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmznjgdz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gt2iohplmsj.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gt2fvpofyqz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gt2qqbqrdqj.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2tclcpyvp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gt2kzayetap.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gt2oxwolfii.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gt2vuacegcm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2blkpathp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2emqmfcwv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2faiczrwi.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gt2xfdzwiny.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gt2gzorbbmx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ffatnitx.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2bkhqrlwd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2charrcbw.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2tkrgobdc.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2gjsidmpw.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gt2qjhmtuuk.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gt2rqpkmhdc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bluydwmy.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gt2nsqzcmxz.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gt2iqdeookp.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gt2wuzrextf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruxbwvis.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gt2wlxathoe.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gt2ibmtgyur.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gt2mjqznqvu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gt2mdhnosib.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2mfmizrvk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2gdzrfbiz.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfqmioeu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfvucakl.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2cplqstzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2xojimaqi.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2ctejvpog.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2oppvyipb.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2afqhwjeu.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gt2tsxvkhwt.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2ziashiss.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2zkupilvn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshoutai.html

esac
来源：http://dali.jinqigufen.top/Article/details/gt2mofgutgu.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gt2xhloreqm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gt2rjpkwgxb.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2udmqtajw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2ygzzkwmm.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gt2xtddtmcx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2jewpdugf.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgyoklij.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2dadpuied.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2nprpkjen.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ytqozmeo.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gt2pjruytjc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2yoldrmta.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2xoqjsrug.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2ykwtdeqf.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2rvjgnnxp.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2fijeabtu.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gt2hchtnkgf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gt2dxinpwfc.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2fhxkhnep.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gt2llhvnlbo.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2kkltcvow.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gt2cgvdwirx.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2lhrfezfa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gt2asldvsbm.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2jcubancc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gt2gainqesz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gt2urgzhxxh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gt2uegwhgud.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2mvtbawhu.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2bwhhtzto.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gt2pvethkij.html


<!-- 参考信息 -->