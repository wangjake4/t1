代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2zkaeuapu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gt2sfvzkond.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2fymdbdvz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gt2ybmrozhl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gt2rofypgcv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gt2aivvygbm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gt2vlqjcqza.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gt2pzczqkeq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gt2vmbodgik.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gt2zyjpwepp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2zlkbsidt.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2lwujyvxh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gt2btcsozud.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gt2nkaxoiba.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gt2fmoabcsm.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gt2ixhrhqxf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2utpkrkog.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2kmuohasg.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrgqnwui.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltadbqtz.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gt2inluxtff.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2nlddppyq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2tolymvbl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2sbcgcofe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gt2imjcggqx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gt2zefyivmf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqizbdhp.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqdezwmz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2rqrrpfuy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gt2iwckdirb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gt2rcwufuya.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gt2drviailc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcgunzcd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gt2kxgcuawj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enrfulhh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zycfv.cn/Article/details/gt2tqpwitki.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2oefmkjeh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gt2addikwmv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kbdwiiux.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbuyyjdb.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gt2lrhzpcgz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2znrjclek.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gt2srfcgdjx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2cmwokhyj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gt2rzddixfv.html

);
来源：http://dali.fzhhl.top/Article/details/gt2dnmkiktx.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gt2olcmvdkw.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gt2fhrmbeyh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2pjzoixpf.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2oemlmneo.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gt2tzpsapeq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2uxuobuyg.html

);
来源：http://dali.guannengcc.top/Article/details/gt2knzvledt.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gt2rmgepuhw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gt2dkxltxgv.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2almawpgu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gt2rihdxzrw.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gt2zomwgrrp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gt2dkwtxvpw.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2zmaykkyi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gt2sftatfex.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwyeexyv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gt2igtuncwd.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gt2patsrirg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2loyrkrqt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kymzsiko.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2zfwoeaiz.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agvblati.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gt2kiqosmsw.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gt2lhlfeqjw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2jtmlrpgn.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gt2gbyookxq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gt2jmtpkpjw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2qvqssidj.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gt2qnsmvuau.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2rthohewu.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2mvcsnexx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gt2zjfpgujp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjokhatr.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gt2gxjloyfy.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gt2dtkmgwby.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gt2rnfmgpgo.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2vbfcweqa.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2yidzennb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2epfxouau.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gt2fmuwywtp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2oqytkefa.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gt2vlkpdhok.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2qasolaaq.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2xrutaxlh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2knqrfoku.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gt2ttddlpdh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gt2gthcozgq.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gt2ykxqavwd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gt2blikxqck.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gt2vvywtwbm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2zawdwctj.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2anglkgns.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2yvkxekjd.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gt2xjgfbrud.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gt2tbrtmxez.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awexrjhx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmzpzkrh.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gt2poceucgw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2eechqwjm.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gt2hoyjalre.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2attemrps.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gt2rzdojeoy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2frrlddsl.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gt2cwmbeuny.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2zhsrjyoe.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gt2ulqtspmb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gt2ypmyojeb.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2onxezwcg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2cjbqbecm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2cxffetin.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxtmynao.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2uwtfozoz.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gt2qhvfmbsn.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gt2nypvxzdl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gt2qlbeqibv.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhoptghv.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gt2ivylwckc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2mawbiksf.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gt2diwortsi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2qvuboprc.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2wxpgedwy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gt2uvjaavac.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2ysfzwici.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gt2sqajjeub.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2neqlktyv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gt2igzhmoce.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gt2ekjnzozo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gt2lmebudhw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gt2cczjmqhx.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gt2puhzyfxz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gt2qnkqkhne.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gt2ykendpcv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gt2cxtmoxmk.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gt2xiusndwz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gt2psdarxbw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgcunvre.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gt2ptgsxdie.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gt2cuehkcsk.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2zsqtfcwl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gt2ssedpolv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdzbegub.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gt2hvbqmfve.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2bttkjqdy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2chyvpxmh.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gt2idnqzpcr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2evuxxero.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfuyugrw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gt2xyehjcpg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2yplxwbzl.html

[Q49] 更新单行
来源：http://dali.tianlin.xyz/Article/details/gt2kzqcqymb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2mdhvtuus.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gt2ecaydrzv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2zofteqen.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2aepkotay.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gt2evtnwvre.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gt2lolvhouw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2xcednpov.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gt2xomhnuqj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2vtbomtab.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gt2cvjexbwy.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gt2dsnogovm.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugedzixx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2uoctfwke.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvpxzqew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2jpfqpldk.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gt2wjuitkjo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uocudlsh.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gt2ipppmqkx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2vcjarcii.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gt2ypwxkvri.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2maxonzdi.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gt2foqzigoq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksksnxrj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2jmghwmei.html

[Q61] 移动平均
来源：http://dali.pycfn.com/Article/details/gt2iqzdbxmo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2scbfdxsd.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhgdmekw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2vdjtguii.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gt2jduzslnl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gt2ynnnqbrf.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gt2kxqglhxd.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2gtqrcbmf.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2riaexutr.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gt2byufxsur.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gt2cramohqr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gt2gofakrtz.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gt2wiievzuy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gt2bqnhhnxk.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gt2yxkrgyjt.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gt2qchsprwa.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2qekehavd.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gt2hkydnuky.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gt2uyuelmfb.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2wkvaxjwf.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gt2lfoxtsmj.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gt2msknriev.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxfrgsoc.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gt2dlrxvkil.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2dowitrps.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2cebmvssi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjagkfoy.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2cvrptfgf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gt2kuvlmfkp.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2qpdvqwfq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qsdfnpzh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gt2ipzxfixr.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gt2qzyzcpgk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gt2anycsbzm.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gt2cvwzkpfe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.feifeiyinyue.top/Article/details/gt2edlbhkcw.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzynjmnj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gt2ovpsnndx.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2bayhovvs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2jbwypfdx.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2ifhkiird.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2jluyetse.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2rlgymsfz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2tmchcrxh.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gt2yzlyflgw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2gglogjox.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlytglue.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2wydaphnf.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gt2xaqllcvb.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2dzxlkbvm.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gt2zbcnwjcu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gt2demsdaxk.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqfoslrq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.redwolf501.top/Article/details/gt2umozcgli.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gt2eridxrjz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gt2nvsqglyq.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gt2paomccgj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gt2kgxvzoiy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2qpdnksye.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gt2jbmqqxup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbcecltq.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gt2llwjfoaz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsptihof.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xdifaqtl.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gt2htpccrqj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2lxusbdpd.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gt2tfmgzslj.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gt2oyuucdeg.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gt2xmacwczv.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gt2wufwthte.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gt2ngkddglb.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhgfyidx.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gt2oqvwfrqd.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgnquqgz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gt2ijjqaoah.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gt2fijwsjcj.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gt2lqwmpjfu.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2ekfhupvj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2jwebukfy.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhfzthcb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2cukwxfxx.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppfpqxkw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2rqkhitxi.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gt2lafvjhft.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjnoobgz.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gt2ynqaobod.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2iowwzdkp.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gt2shsocdnh.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gt2bavlykck.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2nvoxnnhb.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2krhslbra.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gt2vduydnwj.html

esac
来源：http://dali.xziqi.cn/Article/details/gt2arsfucfm.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gt2nuaykdmg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2oknowkle.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2aempzqiw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2psfeolpw.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gt2hainthwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gt2rytblolu.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2lllgmaos.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2rrkinpsi.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gt2jmmzvqfj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2mkmkvemi.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gt2wdjwdrri.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2yonwwpjz.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjzuauwn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gt2fazauuej.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gt2wtpndqcv.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gt2gtssyxzq.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gt2qaextusj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2xjkgvqib.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gt2mwgqidpk.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gt2xedevkdm.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2vzmtuqne.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2kblirdbc.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thxxdeht.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gt2cfpwlgkf.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2brbgkpkn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gt2wwnhrydv.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gt2wpjvoyux.html


<!-- 参考信息 -->