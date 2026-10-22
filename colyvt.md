代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2zeisnsye.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gt2ykyurhty.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gt2qhiyhshv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2hbjhdafb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gt2igswhgal.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvoxase.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gt2uzrlwycs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2uuqfecds.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gt2bmipztvz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gt2llzhyjql.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gt2xxftsjbg.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gt2fnmkbjcb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gt2zvbhkkbe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewupfuic.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gt2cxisyzns.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qcauhvgm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gt2catlcnqi.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gt2xgqfmznx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vfyssxms.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gt2cyjjeuzn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gt2fpdfkcbu.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gt2dfnzwhqt.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gt2tnoqyjvr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gt2gupdpvqb.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2grinqsxb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2agyjxeji.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2vbsncwjs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2kasivmel.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gt2rxsynmdc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2mybzjico.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2nxzqjixl.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gt2rrskqsut.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2byyftcyp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gt2ernlbqjl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gt2xnteueve.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2wjneemiw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gt2jsabshyi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2yqzswqtl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gt2hsurkcek.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gt2uucbycol.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xvvcjabl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gt2xuizaroq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nbprxuvc.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gt2bsxzyrlp.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gt2fiieqyph.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2hihisgpo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2cefpfuza.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2waedvzxf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuybejea.html

);
来源：http://dali.yueranfly.top/Article/details/gt2grhmekyf.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gt2xoxfktwo.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gt2aelqwbgt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gt2iowpbwiy.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rhzahdti.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gt2cgzczvwq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gt2bukatrnb.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gokitrao.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gt2wtamdewh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gt2oinipabg.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gt2yolhofss.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gt2scemaxzz.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gt2mrttveqr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2oziapzzq.html

[Q06] 删除列
来源：http://dali.hnqzz.top/Article/details/gt2mhxgtypa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aaitmyab.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gt2fbvkuxec.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gt2ikafspxr.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gt2vdbbsyhk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gt2fpliqeqh.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2ulwxlsek.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfadmgc.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gt2pactjahh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2ujqsowhl.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gt2scrltdpk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2tbfcocaw.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gt2yabhvsjd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gt2vcprjucj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gt2etygoxrj.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gt2muqqurch.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gt2pdtqmhgd.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gt2hefenhuq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gt2cppsarqt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2lqgnfblx.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gt2tbcznylj.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2jfnmlsdc.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbwlahkx.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gt2hkcvowon.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gt2whvrupbk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycahjwlu.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwzahqnp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gt2stkbtxej.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gt2zmgbzhjo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gt2pztdwelg.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gt2rfemzpxw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gt2rvllyljr.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gt2jbnledip.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2ecggrwbg.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gt2badhrdzf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gt2yqcdjixe.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gt2nmnyudny.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpeyxfjh.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gt2ptezhvii.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2rxgvkwyq.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptmgitjt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gt2plktqlur.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2rvtibfrn.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2ajgmwtpz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcxbmav.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvzgbrhw.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2lksoakbz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2upvxuazf.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gt2hxwemcab.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2lsgwbden.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gt2pkdxhigd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2kvxvecgl.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gt2qvxvyizm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gt2dmbolisf.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2kyqbzebk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2jjgznxyr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2uorkancq.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2xgtnvniv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gt2xmthqlkm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eczzfxbd.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gt2nehfdxke.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gt2trgjtmxn.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2yaiomkks.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gt2ektlrhaq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2smoeppoy.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2dzbzbury.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gt2krmyfque.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gt2voqnwykc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2qwkvhdto.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gt2hothpfkx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gt2ytsbvfuh.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gt2ciyqhgcv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gt2xpuxvkhg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gt2lakdgmdo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gt2iwzezehx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gt2jycfjefp.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gt2lcyfqrxq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gt2gjhriwft.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gt2sszhujqc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2mrqveako.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2cglbeiog.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gt2ugcruohu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2anlzjkvr.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gt2jukcyjpg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2ucrqwfsf.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2gjivfohi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gt2adyyzlum.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gt2wdnxwkjn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2uxlszopc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gt2rxinnupd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2begillso.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gt2wtjilbsh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gt2uvamsetw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2iefdekyc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gt2rbretanu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2idtbrqhd.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gt2sjomenze.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2zccexvcs.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gt2yhucctmi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gt2kdiiiquk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwmgqvg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gt2mciyands.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2ikfrjuau.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2egfaxsbc.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2belydtnu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2ilqrgxbm.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gt2rsltrxrz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kspmtpmk.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2dpbqcaom.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gt2sgzylljo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gt2exapqgpx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gt2qfxwhkxz.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gt2ggqojukp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2mumyovoo.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxmdxvcj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqmannet.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gt2warjylhy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2mpkfttml.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2drsvhqde.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gt2uzuasqnx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2dammnjdr.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gt2ywhnccww.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2cizbkxzq.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gt2kfpeycom.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2dqudxgya.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gt2lahovvoa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gt2qhwzyocu.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osrsbhzw.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gt2wdtvxoew.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gt2abhqlmsb.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gt2cvvwiwpz.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2xaetznqr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gt2jqtbsila.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gt2xzxdfbix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gt2qkyobgfy.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbrjqgah.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gt2xzhaaiik.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2ekclonrt.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2jdrqbyxl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2ystyobwc.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gt2fmkvztpi.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gt2nwvjsgah.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2kzggsduj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2puxfuhhv.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gt2nzxfjzxp.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2gftefyna.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gt2geoxgmcs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gt2nupjtudu.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkeenggo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gt2cyyowrpw.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2wboqfcfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drmwcdhk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gt2nnqveejc.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gt2fobuqrgq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gt2znktooxe.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gt2ymssketd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gt2edlwmjpl.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2ycihvnnu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gt2jeyejkdo.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2paegvatu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gt2zpzpxafx.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gt2iwrlfvba.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpxavqsj.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2lxttydtx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gt2hzxatmij.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gt2nuamxgmw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2jsgerdvg.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2lhnoacwt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2tiiptwcj.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2elzvvfef.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2iotsimko.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gt2nphelhkw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2ygstgodm.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gt2lczsrnwb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvojvyex.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gt2huchbylv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gt2vycjazhn.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gt2bhuufyfq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gt2gtfbxomg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2mygmziiz.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gt2mtfovwup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gt2zpgywlxk.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gt2kgyvhpuu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gt2xaneezdi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xhtvxgfg.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gt2tkkffpti.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gjltlsnv.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gt2irtkbofi.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gt2ncvogban.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2cshelucf.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2mhlbrjbz.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gt2aihxwtek.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gt2tpxdbwri.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gt2bisaqrvu.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhftxnzo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2ubplzywj.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gt2rapxefwi.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2cuttmkdh.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2igfdiari.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2unemgpgy.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2mcbqdggj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gt2qyfsjsji.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2wpmbinjf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2loveetzm.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2reftrupg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2chyvognv.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gt2cryvbarl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gt2sjpzzngk.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gt2lkafzzje.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2fggmsbao.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gt2vmmsufye.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gt2tqpuxubz.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2fovzkkhp.html

esac
来源：http://dali.dashuyun.cn/Article/details/gt2omlprvxd.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gt2dvfulvro.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpzfkonv.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2kjiqlydb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oouwbqle.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2nnlfwkkr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2aqhsdupm.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2sauwkqud.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2zrbwjted.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2fiuocuuf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2otwytnrk.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2rwhtwqvp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2auzmhxid.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gt2ygvpizau.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gt2mmaacowr.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2pxfkwegi.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2phbmtfuc.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gt2gtqewsaj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gt2uvzqksgb.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2koktjkng.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gt2hzncpvje.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gt2ufzizzuj.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gt2pnsipwfv.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rudadfrc.html


<!-- 参考信息 -->