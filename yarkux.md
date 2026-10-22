代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2bvgyrjzm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gt2mtuslnvu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gt2fpwyjiia.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gt2yqxwciac.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2umerzfwr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gt2pbhmvluq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2nyzvsmvm.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gt2agouricf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gt2rrhuamxa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gt2krxamplp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2kfabcikw.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gt2mwazahpj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gt2smsoonoi.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2revlcdou.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wgplqvqc.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gt2myvpwchr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gt2tiafkwmn.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gt2qnrcdeiw.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gt2zygwvoeg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gt2ivltqwbn.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gt2dvotyrro.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2ddygsjzl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2yaohyblb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mbgvpqkm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gt2tdmkmbjo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljoxglft.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gt2brzepnlb.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gt2kjqlhboc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gt2rbypypmx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gt2psexunzz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2ubbkweym.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gt2kfunvyfd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gt2yeajlswy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gt2gmbqkqyj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gt2qroftxlh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gt2oehueelc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbyatptq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2cgrlnmmq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hfssgemj.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gt2vswllssy.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2htdmokfq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2mpbjmbyf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2jcvfeyeh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gt2vzkcchbg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gt2uhytvrgb.html

);
来源：http://dali.gzhubu.top/Article/details/gt2yyczajwh.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gt2tscgupee.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2uiwyzwmt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2tylfznyx.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2anvjcbrh.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gt2kopzppry.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gt2eylzyyvo.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsglviam.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gt2pshjnada.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gt2idbsmwlp.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gt2harpudul.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gt2qkazvigl.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2svffrjym.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wytjntix.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gt2awzqdche.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gt2xuriwwpg.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gt2gbgyoxtp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gt2ergioaxz.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gt2ndscvckc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2cvmaoawn.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gt2rnejkfwv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2ecueaipw.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2adpuysma.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2vyxkhsvx.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gt2iyveveqt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2smqdtlaa.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gt2zupdbfrn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gt2xgajovsw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gt2xssvrxpj.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mprxeujo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2cksnsjvl.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gt2fncuydnu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gt2drkmvfmv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnqzz.top/Article/details/gt2hokrshem.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gt2zwskojmz.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2yhwpndpx.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcsvcwul.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2jpgudnwo.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvaddqne.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2jgelgbtb.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gt2gzkiabwt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gt2ogbojdkc.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gt2aqxeyrvl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gt2jcbpmnkg.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2qbcljmgy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gt2egtzpaiq.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gt2olozqpdb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgihzlgi.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gt2sxufcyti.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gt2ehwwnsjf.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gt2ysvfprzr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gt2uduolesc.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2uajxnduu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2xnhqmled.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gt2hnoxzszw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gt2gtmrmqfo.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gt2vausuwic.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkdphuda.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2dotdprao.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2iesisqmc.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gt2rdbwtyzn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2vvgqhzee.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2aczbjfam.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idsotqcx.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gt2kwddnwfy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2kutellpg.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gt2bmbiyowy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gt2jpsabukq.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2amcheiqf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lihsaein.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2xijwndvl.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbpibndg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gt2qbwhnzuc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvwwgxl.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gt2rmmzabjf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gt2txddwlwm.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2guqwlgvc.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gt2gdyatqbr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2mjrbaeci.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gt2wqbzzlyk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2azzwsccp.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlzktopz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gt2tjnqnoix.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gt2szdtckrw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgxkumgw.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2alqhflom.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gt2pokjkvkn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gt2kwvnohvi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gt2xwjrydmp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvfpnlzc.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gt2ddulstrv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trctwnhi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gt2fxqmbqdd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkiohfgq.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gt2myivakwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2mfqxffuq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gt2qpkziijy.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gt2vhmnwsmk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gt2emlnsimw.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gt2pfxubtze.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2alkbwkbk.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2nqqsxxiz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2mpyasbwx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gt2bcdwcghs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2fwpcpxgc.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gt2kmtjpexl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gt2jceqfyeo.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gt2zwnepfcw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gt2qlfiseks.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gt2bykzhyka.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2gizykdly.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2zomyamhd.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgbxtfeg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2wrvdmgyp.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxqijmkh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gt2npobdyiq.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gt2xikdzvfc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2chlqwzko.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfkzkgon.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2txnnsjxh.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gt2poaoxewd.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2uymfghtm.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gt2xqivlkeg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2oncngxnf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2qclhqfrm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2vvamnftz.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gt2lncvonoi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2ostnxmwv.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gt2gyyzsady.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2kzrjppcj.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gt2zplrehwq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2nreryrsw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gt2xvhrvrba.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svzaafit.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2ulcycnbu.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gt2tulvnhsj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2hqpgzeuv.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2qmadupnf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2azcztksp.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gt2yswrwjcc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gt2vsgsfghc.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zecaqhfc.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gt2nmerfkal.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2xsispvlg.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gt2xufbnhqd.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gt2gbagkhcq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gt2ttpsoyqy.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezvlucyn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffrcboda.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gt2jpllyfxr.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2hupqjwnp.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozaqwmva.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gt2roeuolua.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gt2knvrishc.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2ptpqdtkd.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gt2jxmvkztv.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gt2admdmlfb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gt2jperhyji.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqjimmuk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjddemjt.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gt2hqmpmmon.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2glsduivg.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqwuducu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gt2vwsyojue.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2ydloctdv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2cwfrmpit.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gt2kbrdrqgj.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gt2hewgxhhl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaxcksu.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gt2ujjxrsjk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gt2shetzzdj.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2ntxikkyu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gt2fxhcsvef.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gt2rrqkkeqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gt2hejjbpcx.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gt2bvcdibhb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2cljrolhz.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2lylkwibi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2mghonczm.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gt2uxavmlqp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2alvakaqy.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2lwfyplzp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ykachmfw.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gt2lzteqlwp.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnebuapw.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gt2jhiqfgyt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gt2unhufpix.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2blgzcjew.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gt2hqqruxeo.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gt2mknkuvsu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfftciz.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gt2xecgfkcj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erynxkpi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2tezjsyge.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gt2hfhuphwl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gt2ldoxvgba.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gt2isdcgrjr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gt2ibpraafq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2pibtffkr.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awwebika.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2jxbayvni.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gt2gryerrkb.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gt2dtpqdkwa.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2eskwqnzq.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2pjmtjzrb.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gt2aodqacye.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gt2rxjfmory.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egnoxdhw.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2uhbpgpny.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gt2sdtsqkhy.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2lvnqjgqe.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gt2oxyxqelg.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gt2pfbtquib.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stlvuigk.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gt2wqdasbkf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2qwhtbcek.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2txnzrrxf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gt2znenegot.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2gqfaekiy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2rqgfivrm.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbtzomtg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2omrbbspd.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gt2syvwfcvv.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gt2fbefcdxl.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2gvxgjupm.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2blkpjkja.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2ziexkfzj.html

esac
来源：http://dali.jqgfzy.top/Article/details/gt2pciddiqw.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2ljjwdmfq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lowdtzkz.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gt2jyxinial.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2wyvvzgjc.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2fyplrflu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkzuiwio.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvlzoctz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejzyghsp.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gt2krjcossa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uystqblp.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2uwhabwhg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gt2qnvelmme.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gt2btouwsui.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2syghktvc.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itioclgr.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2cmvdlita.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2pvnhihij.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2gmfrrgve.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2rdrtvvfl.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2lgquxgyu.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2qryxaupc.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqkvbbek.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2dmrldxge.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gt2hacnjgyt.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2whuclhmh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gt2xkznwpsz.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gt2xmdixckf.html


<!-- 参考信息 -->