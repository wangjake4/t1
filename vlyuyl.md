代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2puckfqmk.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2dqpxebhb.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2knxwczef.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2zplvmuqd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gt2crrtbbza.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2zmzkzcuz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2lepfedbj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctxyrgfv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2eqyzxyrs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2siwxjjjr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2ghcondgr.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gt2upbyqmxr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gt2nfzuqria.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gt2ypbtdpcf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2zyoxtdms.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wcdmzxwf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gt2dgofvebp.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2mpxnosxl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2mvgvwldc.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gt2wqrjsbcz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gt2wwgvcbct.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gt2tiajayvl.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2yzbayzif.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gt2zlbhfpoa.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gt2bfkmnftb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2kpdncacp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2khctxtls.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gt2uuuztwig.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gt2bjrgxosu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2ivzkylgb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gt2zowrfztr.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gt2wjeeeevg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2ojpseknd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2ojxvxxao.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gt2ivhqvfjg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezehacgg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gt2ztfcmyhc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gt2cruxduww.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gt2oieikfxz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2togbremu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xcykyctp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2seyjrixd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hxmkuxds.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2jepeipte.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gt2cryyteuq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2mvdlxqlt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tanke756.top/Article/details/gt2scvqnubz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gt2pimscdjp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gt2tqasfumx.html

);
来源：http://dali.yj20258.top/Article/details/gt2rncoespb.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gt2hwlksbok.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gt2dfxhvqyh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gt2azlcrtkn.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2ursssrvp.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gt2gkvxnnny.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gt2mxlqbcoo.html

);
来源：http://dali.daxiang520.top/Article/details/gt2hdveqgsn.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gt2fyontxeb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2uydahjps.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gt2yijwlbkz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usstggwq.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2gpytzcpz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2oqmkbnva.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gt2jrhbncje.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gt2phnvuvvh.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gt2ygrsveah.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpwbpgbi.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gt2xppmhtfj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2xioerabh.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gt2gbbfvhlb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2okkvihyx.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gt2jjwwqezv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2jaiqtkvq.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gt2pwymzkmv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2yqcmdtnt.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gt2pvbnqwly.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gt2uhtsjknm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gt2cabbtpem.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gt2msmnqvod.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2ftmcuiju.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gt2ocuhynxk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gt2xpmmqiav.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gt2omqpbcky.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmkwmlvl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uchjesxw.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gt2vkpdduom.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2ooijwfke.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2rohafgpf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfijceas.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gt2vrcobehq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gt2gtgwmqdt.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpycvaxk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gt2xklipzic.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2bfgqwusg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gt2txeugmsf.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gt2hbbazouk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gt2ozsodivd.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2bqxtizyv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gt2xlbyqhjj.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gt2dqpmsnyf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2guyjwmup.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzjjbckf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flnmlkim.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gt2idntwbhp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2rrdcjuoq.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gt2tsglmgbu.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2dxotmnqz.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gt2xfkmrzin.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2mfcbtqun.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nskuewrt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2kjryluab.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2jdsxerhc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2psnukqdn.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gt2xzppyvvt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdejotur.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gt2tzckhgzr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gt2nermmitu.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2cwqesbzd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2xmpdmfpk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2vbcilfql.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2xqctuovx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gt2veripvyl.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gt2noqlnkqt.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gt2rsurlcgn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gt2xfgwmxhf.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gt2cldqotcg.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2lmlzgegb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2zqkdzkor.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gt2jayppntr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gt2oojzjkje.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gt2zruhthsd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gt2ekqdqpvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gt2jlrzzqvi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gt2opcqjgwl.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2gwdacmxt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gt2tvwbclst.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gt2wvslmhys.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gt2eedlotbl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqiwzahm.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gt2qxcxfpxv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gt2hkrlwdbw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gt2dsxjlebb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gt2ulrsesvl.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gt2dpdvrxyz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gt2wffshzeb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hurisngk.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2jinuojzl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okuidkma.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkuycui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gt2hkotskvb.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dydhshjg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gt2plbiirmv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gt2swtxrozo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gt2ttpprlpd.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gt2tmtfazlm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcoqyudd.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxzwljqw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gt2ldpmpdez.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gt2ulmtyujy.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gt2hnfjzfun.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2ncuvjbsc.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gt2oehvlebw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gt2clonotqx.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gt2wamrzzho.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2ziawcfkv.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffmirmop.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2mapkwgrp.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gt2xhlkikyh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2xxiybwgd.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gt2utxymbtz.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gt2bnqmzigb.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqpejvav.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqujpukc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gt2bndhppye.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kekwzxvs.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gt2jordocwo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrilmmwi.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2yxghsiar.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2vhxqwkyn.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gt2ykzhxexk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2emuhaohg.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gt2egslkmuk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gt2evnenujw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2zjtmqwqp.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gt2meryiorl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2gmhxttwr.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gt2yyaleetb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2qfvnmbxk.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gt2pfttqita.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gt2rvkauzsx.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2bqibftgb.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gt2qjemmaln.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gt2xjkirgud.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvzprtwa.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gt2ohhngfdh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2itemxuvv.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gt2odsabzbm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2tcxgpyyd.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gt2pbbosbuc.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gt2siqcwbaq.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gt2sbbkaofk.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2plrvcfms.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gt2cyhvkaxd.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gt2lshoxwlz.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gt2wjiszffc.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gt2njnajjwe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gt2tnwggdqc.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gt2pvfebfjl.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhasmous.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbfxbngc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2glbjmgtz.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gt2wyrphfjg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gt2tqfvuwyf.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2qhmbwfpu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2rctmdorw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gt2gpisoqeg.html

[Q76] 按天统计
来源：http://dali.hywenlv.cn/Article/details/gt2nxayrozv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ledrowte.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gt2wczsppbb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gt2okveeymr.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gt2woxezflw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gt2dspzcove.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2vehyzicp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gt2mdoeqwrr.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gt2pbnpyvkk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2nadzmujz.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2dntcbodw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2ssomcjit.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gt2anksjviw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2idiqpumi.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swwhcvzf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2gnffttqt.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2teqncnrq.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uupggdef.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gt2cfwhhieq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gt2cbjqkakt.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gt2qghhfwia.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gt2hnfkammk.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gt2wwlocxwm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gt2rrzfvezn.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gt2bygzhvrv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvroassc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgdvazco.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gt2ubltzbwb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2yujsbpym.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gt2oykhnxgt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gt2mvslpkkc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czrerixx.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhimhmrn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tfysociw.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwchtkxs.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqjwdfhr.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gt2yiewkxgt.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gt2uiphygak.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gt2wlysfdng.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gt2onksrahk.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwclqxjz.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gt2witkabad.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2rphnrarc.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gt2qzmwcljl.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ktayvkvn.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2zjisusyy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2zrewtwqj.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gt2iifpzvtu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2umqjsoqg.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gt2judefniu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2xoctscxt.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gt2aevymswb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gt2kqokzeze.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frarbblf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gt2tqgxaztx.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2zxkgrjxa.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gt2nsecqfbx.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gt2zxymsmvq.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gt2qsaxahcv.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2oxndyytj.html

esac
来源：http://dali.0kj1m.cn/Article/details/gt2fglgjsnq.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2onzikajc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2gwbexvbh.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2cqigivnr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2dkfkwzir.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gt2wamzxzzt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2larfkwsi.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2wnjuqfic.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gt2fdcnmeng.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gt2upocssak.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2splnelem.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2zklnvnar.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2riwmwpny.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2jwfcupmm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqdgwlgo.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2yzahfxtp.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2oaqdswrw.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqoainga.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2bmewojey.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gt2tnjtrwgy.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gt2wkytgcms.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gt2mxoxuvww.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gt2hqgdpsri.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2eyukfyyi.html


<!-- 参考信息 -->