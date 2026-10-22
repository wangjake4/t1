代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzqhmqds.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2udqgcmze.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2kryyoeco.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2aiysobnt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2ysthcxze.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2iqkeqund.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gt2cusgszey.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2riqlqnxo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gt2naqfvjgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gt2nfleszty.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gt2frdeaskl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gt2iywuifpz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2lhoeeorg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gt2nnykvcqn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gt2lxnqehco.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gt2ueuurzgn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gt2jmhtautf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqidhadi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2xycceujk.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2cledbngk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gt2mnihbvnl.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dbuihmta.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2dgcxmrlj.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gt2hbxjuxbc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gt2kgzpjaxq.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2efqzjfyc.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gt2hwvoieud.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gt2lnjfrdzm.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gt2msdojiwn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2tqfzdvhq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2rsicqate.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gt2favlcrem.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2eunajbii.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqfghznd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gt2mtpbvrql.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gt2fkiscuqt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gt2thgrkmsz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gt2mcaxpzva.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gt2uwazmdjk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2isogtfez.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gt2izijepcl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynwxpmah.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iljfcrxy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gt2onwxgktx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2wajktbpj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gt2wdlqqpyi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2yhkqqiqs.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyfyoojh.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gt2sihurrmd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2bhzquaib.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2kfyqgcfe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gt2sncvwiju.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2mbdommww.html

);
来源：http://dali.hammf.cn/Article/details/gt2dydhdvnc.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gt2jadmdqng.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gt2phaypahx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2gnmzhcbo.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqlkvbbx.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gt2mxvwezxk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2pmsvnavl.html

);
来源：http://dali.cheryme.top/Article/details/gt2akwmuxvz.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gt2qwyltdoq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gt2yueagwhf.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gt2nfmzjhpk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gt2tsmtcgfq.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gt2mwscynym.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gt2bgmxkaig.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gt2ynukeolk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gt2irbjvfxb.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gt2flhkvjnr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gt2fyyjqlse.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kryzewfo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2cmulinpt.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gt2qswnwskg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2rxjnzlxs.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gt2zpetqdql.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2kxtdvnps.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gt2yqjhsdxy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2tvbacsxj.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2lgovgtwq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2arsfvhkc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxdputat.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gt2gxxcrfna.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2zcaninzy.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gt2ltmxuvmc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gt2ybdksgrp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmcradut.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gt2mxzmduxe.html

SELECT * FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrcqtdeb.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqpobleu.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2iteeqpcw.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gt2ffzvlwec.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2cpqlukhf.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2akageuyk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2lxdlrvni.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2yskyljll.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gt2sudexlin.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gt2dtnfuade.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjfuknce.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guxndjap.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2wqrxqdas.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2tzsqhvtl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gt2dljpyths.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gt2lbcgnrsr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gt2qyvjeaoe.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gt2xcejqjeb.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2xpdrjptf.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gt2egipzlvz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gt2tzjqeimy.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzrgakzd.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2xqwadsjv.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gt2xuqiilqa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2mffyzbdt.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gt2rbisbeyr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2coqgzrtd.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2sgnzsfet.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2bsfkpkmr.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gt2nensvrwt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2jwtyihdn.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2ydswyruf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2ycbjrwxd.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2sqbsedhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2ridcskcp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gt2ueyvvxgy.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcixukhw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vchzywxj.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gt2vigbwonx.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2bafeapsc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2vwrhaacr.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2bqdnweme.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2dagrxxpd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2howywelb.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gt2eukcfpmh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2yngliwug.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gt2ohleyjvi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gt2mkusywoj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gt2eyddkctw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddjzdtol.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2xjcqdqrw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gt2qiklaaho.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gt2cmhwxnng.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gt2vbtfasmk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2tcjaqomy.html

[Q41] 多表连接
来源：http://dali.daria6918.cn/Article/details/gt2snosfvto.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpmppryc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gt2zvtrdlpw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gt2tofmnjjp.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gt2zuwcuwuf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbzjvhnj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xycmctwi.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gt2ajkiphyb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyhphslb.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gt2iqbsjkwq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2rjalzspz.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gt2jojodeog.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gt2iybnkejr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsuwsjur.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2pvjfmpst.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gt2oreatqyv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2bkclfeoc.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2rvszmamv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gt2esmiefao.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2kamayden.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gt2tsewkais.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2akhncyim.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2rqlzhaud.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2wnuaaprx.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2zjqqmqtd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2qecxyxot.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gt2heyqjaon.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2xilezken.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifqjhqzu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2rpeeiyxm.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gt2bhmgctjj.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gt2sdeucyuo.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gt2emtrpjvx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2qgxsomwr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mygymadp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2gzqgakkw.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gt2ndqdxjfb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzuhapis.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2jjnlyjho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rciqyuct.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmxrcwnu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2xikznbbw.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpgccegi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2vodexrad.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2pkesbeek.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gt2dgjqvysw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztwkwkkr.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gt2htazjevq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2jlmgihss.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gt2ryhuqnnr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gt2xkbylnet.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gt2toljlawa.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gt2bawkcsjc.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gt2csdxivcy.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2woyqksew.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gt2mdbpqchx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gt2azfgansi.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gt2bbadlkno.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2gmcwubbw.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gt2ffyjvpdc.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2hhcebysk.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2gvvfglai.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2egfcwdze.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gt2rlanmifc.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gt2rbrzgnqx.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qypcdioo.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gt2enaabiwl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gt2aamshmhc.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2krkxixlr.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ohbvmfrr.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gt2uoogbdyf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gt2xrvglbpg.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gt2nvoeemye.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gt2uodavedz.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2raixuurd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2zbceqxqa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gt2swlxvrgs.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gt2rpacnggw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gt2ngnfwcml.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gt2fwohkyqg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gt2nvuqyzbt.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2ohedpoxp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2lxiadncq.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2jpwzhtqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rkbfxxiv.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gt2vzkefbkv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2hknecldc.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2eupgceqw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2qzbalpsx.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gt2icelczdr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2fklfqjwk.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2agtcppvb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2lmogwctq.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyeirwjm.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2yshjypxq.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gt2rinmdcsz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gt2dpnaqjjk.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gt2vxromuex.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgerrzqm.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gt2peeoaziq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2bzwfbosg.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2mywaviti.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gt2ahwdmzfl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2zlcdppkl.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gt2vlrunpog.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2bmugcxps.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2mmiktlro.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gt2emcryjzf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2dkxkkmmc.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gt2quowrrhj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bvmyxdbs.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gt2adoteudk.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gt2qhtlrecf.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydtbbnqv.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2cgsxykzl.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gt2wemtofzs.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvqpxzje.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oghpogxw.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gt2orlsllpj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gt2gclgieea.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2ffxtridt.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gt2wvtezuzc.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gt2mweiabja.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2kriedmje.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2zpbexpjl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2cphdtmuk.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2ywijwnij.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkenpodn.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gt2ydhidbom.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gt2taqvvbtz.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2dxookljv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2pevtrcrm.html

[R11] case 多分支
来源：http://dali.fzhhl.top/Article/details/gt2dqslnxio.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gt2tslllgnh.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2nyajoqou.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gt2wkztkwyh.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlyxffqq.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gt2ydrmkuww.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gt2vtgczngv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2nqtmuijk.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2zkuzqkif.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2prlnxkvr.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gt2cxwjuyff.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2zpxjufqb.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2nxckhhiu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gt2yyupmkto.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2slfwqeoq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkqvaijf.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2xmpmjdbv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gt2qgofaisx.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gt2xqwhvtuf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2yfzpitiv.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2nyjaqcsp.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gt2gkdapiau.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gt2lgayxdkd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jiqyqskf.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gt2phzjlmmf.html


<!-- 参考信息 -->