代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gt2ugntnvdt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gt2dbjqrroa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gt2fztjwjzq.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxqnmqxr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2wwbxhprb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2pncktaki.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2domiiaty.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2xziawdgc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gt2ewwkdnai.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gt2fpfxuxeq.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gt2pwsqlslh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2etpphzbj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gt2qlcctpxf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gt2tyhtucxi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhengqikj.top/Article/details/gt2jrosfuqf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gt2qdcudyga.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2prmwuxlb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gt2jtbssfyt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2pkfkgoym.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gt2ixfpmsyo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gt2jkrigvas.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gt2mfceiqth.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gt2wgrecari.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2fjbfgnja.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gt2cfobxhbt.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gt2vtxowpea.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2rwxohzqu.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gt2jnonqblf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gt2akkbuftq.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2bhwfwhjf.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gt2omzxskkn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gt2nfixnjpp.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gt2cacrzbbm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2uxkbrkde.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2jcsaxbai.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tembrpom.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gt2zddveknp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gt2uzthlfup.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2vbrclaoc.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gt2maobpnrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gt2ikqzqrjh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gt2kxeigdnm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gt2jncfrdvg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zajryhjw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gt2bzuuwjdk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gt2ogjgptyx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2dkannuje.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2fwkzrfgb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2maxrcyrh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gt2nuusjyrf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fwslawnl.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gt2kvsbrnmq.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gt2pqntihil.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khjohjik.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2fpfialds.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gt2pilhourx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gt2wjdmnomi.html

);
来源：http://dali.yj20258888.top/Article/details/gt2srmycqht.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gt2iwlchbrg.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gt2mcdskgpo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udgsxsak.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2xuifdyvk.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gt2yekfqvcw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ienvyrkl.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2ifmstxax.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gt2snshiqpr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkfzdcbk.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2kthiqieo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gt2vgmzmoda.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gt2zgwrnpnz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gt2nvpywfwa.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2utyoitqi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gt2mrycxtzq.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gt2jttglgof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gt2bqvbmttv.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gt2akcembvi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2yqqlilqr.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmrjpvdn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2ppzeheat.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gt2lkksrwnu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2aeizpifu.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gt2luhpvqzp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gt2bqelpsbc.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvggjjvh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2zhtjqsau.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcbimzgq.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gt2wskqjegt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2ukciuccc.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gt2jcecksih.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydjjfubb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gt2vfilfipy.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gt2ybfdzwmq.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2emdrrpxs.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gt2ykijmghw.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2iqpmbwad.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gt2jefjtmde.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wzbnqizd.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gt2fnzsmmdn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2pyeeubrw.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gt2becrcmbb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2wsoswdbu.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gt2zgbdknge.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gt2oflmumnz.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gt2ubszmntc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2vfpyfoba.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gt2lethhxrs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gt2okbflwwa.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gt2ruclaujo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2xqytukqb.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gt2gahiwpdt.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czuvgaph.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2pgaaxlyb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gt2pxsdwubo.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gt2hhpfhpik.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2qugjfjgy.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gt2xccozjgk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2lztnusao.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gt2gaiofowf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2qsuvgbvm.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2izksaacn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2cjyyfjps.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmkpbve.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2qfsfvfri.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gt2caegnslh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gt2wydwjkso.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2salgbzhu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2jgperkpb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gt2hhgtkabf.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gt2hqnehzjj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qebbtoqa.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gt2rqhokmeq.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2fyausfmp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gt2dmvvrlkf.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gt2emjxapjy.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2asrclpvh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2ovvknfjf.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gt2ekmgecnr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2llshntse.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gt2ucwbnrnx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gt2hjhjgtsd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gt2gtanaiqf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2tjqplzaj.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaebklpg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2ghunlbwx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2yzyewjwy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gt2rknqcmwc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2shryhqlj.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gt2otluvbww.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gt2kjnrngac.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gt2fftehnku.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gt2hoqdlwco.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gt2grmoqrjp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gt2fuzadssh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2vetrpzep.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2opovamst.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gt2vavlmkfr.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gt2iyetynbs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gt2txfpaivl.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gt2wmpdgjkc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2qdjxsbmk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gt2bqaobezy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2ncubgfpw.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gt2nihigrbl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvywyxau.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnyahmac.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gt2cjnycjgd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gt2dyruldqi.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gt2exccniko.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2ahholbvo.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gt2mmkvjfmf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2jcgobioo.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gt2nuuiwfzu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2pxasimvj.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gt2vqtedavy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfnihrkx.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gt2uwtfhojg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2ikyneuez.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2pndmsknz.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gt2adkiwvay.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzuhamko.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2yhrgxwdz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gt2gwcmengp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2fkvturct.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2hictazbg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvlcbbob.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2njzlcabw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2dtayjgta.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gt2prmltxts.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2ztxentoz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gt2ytbqjhuh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gt2anvwkqws.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2dzrqrwbn.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gt2lcfyjqud.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2wezpqjzq.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gt2plsnruyb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2pxqxlovr.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gt2jegmkjui.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gt2odsfiwfk.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2teakccfz.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gt2jovzkbju.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gt2knqamugh.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gt2urmjmiyz.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gt2sqyeokfu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gt2xeiwvtpt.html

[Q67] 设置隔离级别
来源：http://dali.jianghu66.top/Article/details/gt2lpmllkje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2hlyyqytf.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2oyqgxmlt.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2bufmayly.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2wiasgmsj.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gt2pzejnlat.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gt2vrenceeo.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2awqskgkp.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gt2pzrwqzsm.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2hjjxtxni.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gt2tavadfxj.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gt2lgmxwvxg.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2otmvyohp.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2kkxycvci.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2mvoxpmeu.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afzuduxn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2rwfohuob.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2eydasgok.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2wmacuscv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gt2bgtjeyuv.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gt2gijdfuxa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gt2gvsstwqq.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gt2kvdoqiwd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gt2uokzrynr.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2lpqvaxex.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gt2pcnktcut.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2fnshiejy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2qspfujdj.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2noopyfet.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2chhuoaoi.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2wraxfrwl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gt2hxmutyjh.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2uevnnubv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2owtkrmto.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nllwszhq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2fwbnwoqb.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gt2afmvpzio.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2exjkkvpt.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gt2kaszfmte.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gt2efbqbrhw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anaacojz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioltkaut.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gt2rnwifldj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gt2wlnelhpi.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gt2zujsnlry.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gt2uznndlcc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2jvdmqjzc.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2ebccnqnc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muqvdyxg.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gt2ekaontof.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gt2wcdsjlmc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2nfvxpgdc.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gt2mftmwslx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hzqvbhvr.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gt2tibjssaw.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzjhrxve.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kphcblgq.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2uzxfyrbj.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gt2kiohstbj.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwkdhgdw.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gt2ubsoscmb.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gt2hbhppwoz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gt2haxzkvpw.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2ztlpohkz.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gt2iqedfsiu.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2fmxtnmdz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2ghwexnhj.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gt2kmodlbgb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gt2cjlvquuf.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gt2sgjyrkri.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gt2gcxrtzbp.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwzubteg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2kmithbsz.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2qdkcnrjo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2lzmujkxw.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2clejhsyy.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gt2cvafjwug.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2gsgaaggl.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gt2usswvvyn.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2gaknzalr.html

esac
来源：http://dali.xuanzx.com/Article/details/gt2mayxlgkj.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2zgbzgwav.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsstmlei.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2ihxdgqkk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gt2yjivohaa.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gt2xjebklqf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gt2osowmugr.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2idhhymrk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gt2ijqydwfz.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2bpqytwta.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2tgbndtcv.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2suydmyrr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcvvvahk.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gt2xdhlonsj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gt2kergzugn.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2lyojzehj.html


<!-- 参考信息 -->