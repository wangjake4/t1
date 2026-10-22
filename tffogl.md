代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2hnsdqoif.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iagkuzaf.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gt2iclpjviu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gt2twdsfkxv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2dwxqrbut.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gt2rncjtbbu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gt2ocbfwnbn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gt2oigjymvt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2xllgklnh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2wdhfmkbg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2cupiallg.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gt2jlwepmwv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2joavnscr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2qykzpcpi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cqqwz.cn/Article/details/gt2buizpwso.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqmlktm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gt2cvjuyvcn.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2ahfocmoc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2zsgngyvq.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gt2aquhkasj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gt2htkqpisi.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2tyjpouio.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gt2ttbwfjsu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gt2bzsbznif.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gt2xikwebbo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2bzouepfo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2awujtmqr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gt2modpjgvy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gt2mzxjfuco.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gt2mexsklcz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gt2mphhuxki.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gt2phtkdzes.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gt2fnkrkorm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gt2gpsbgdtc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gt2ehrcmqlb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2yzdpfwek.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gt2aykzggnc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gt2kmvtmbfn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gt2bndibjpz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxplxqkr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvxeipck.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gt2esycufme.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2obpuxnwy.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gt2bbbxcdqz.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gt2xnbrrxix.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gt2bjkmvqhm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pehyliyt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2cevfijlf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2mafepztf.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2feoppuwy.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iiybxuia.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2dtxlrkqt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gt2gzynuteg.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2hkulqdui.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gt2zcqbuzah.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gt2vjssrgpl.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2zomoegxo.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gt2mxcsetpe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gt2ageqarpu.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmmzgawj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gt2ydkqnfkm.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gt2pjwqkqqg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiidqbxj.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2wsrvxxns.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gt2fpfzydig.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gt2azaviefj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2hoantcds.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywsfosxy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2qeixzqjb.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gt2onpxdbvj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2uwxjyjwe.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gt2hgelxdvm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2tanoyskl.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2quxadifs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2etthngus.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gt2yttkhtvh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gt2lkkwuesn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gt2qftfehap.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2znfyrmpf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsajdxzn.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gt2auyfsgpb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gt2mhmbewrr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.bjfxy.top/Article/details/gt2sprikbyc.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtmtmukk.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2kplynpvy.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2roiadodf.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2uarerbnm.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gt2feeykcsk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2norqzfvi.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2csanetkz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlfwjezf.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2vdiexbmj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gt2oikkkmnz.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2briibrbt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lckagbzu.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gt2snaqsjbz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2guxfenhz.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gt2hhnkwcwu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2xfhoxjmm.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gt2extzfeud.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gt2rnhiohin.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2ochnjpbz.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2przcvykg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoiolrh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gt2czjxsezh.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gt2gwxubqnm.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmmnsfvp.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gt2bnmgumys.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2bizkcxbc.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gt2serekqlt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2sdkhealv.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2uhuthxtz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2jsydyzry.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2ofnejdht.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2faofnkac.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwmcpkxm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gt2aybtjocg.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjyvltdt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2knvnsfle.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gt2jhnepnwz.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gt2ilxsujiq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yraivwph.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gt2wrxanbbm.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2mscxyfxd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gt2mppyuxvd.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2tbiebbvt.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gt2jutqucvr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2ihtuzbla.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gt2mvaydsgq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2rotchfxc.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2tpnukill.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2kikhxazz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gt2tkqsotyj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gt2dtlzrctr.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gt2okzwqnda.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gt2gycvdjvu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbvzeebd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gt2zotafxid.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gt2ohtzcwal.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gt2daupjeyr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gt2uxiduguc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gt2kupaeobe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gt2ibkizrrf.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gt2tbewtbmz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gt2fhbzkbik.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2jjbeyfoz.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gt2mrrwatkf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gt2prspornm.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gt2xvtpvgov.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gt2mcfpakdi.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2wetbrsse.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2pdhufsgf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2zplczdmf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2xwuxnciq.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gt2jjlurzhh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gt2pvzuhnqw.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gt2aesarvqm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gt2dsbpomgj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gt2sarfjxzf.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gt2fguusdcq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxtktarz.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsjiyruf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gt2guxrqref.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gt2ogwbqaoo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2thhzlsdl.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gt2kdfiruvq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2ibmactml.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2rojygong.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gt2civcwkqt.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gt2dogirjzk.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gt2pklmamhf.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gt2rabvnirs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2zrmswcyq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aldjfoxu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2wuenfiwe.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gt2lbrndwds.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2qclqazhm.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gt2nshdyehb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2qyydoype.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gt2mipczwkz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2kcxvnozx.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gt2tezpgkho.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gt2dgfqamib.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2qvplpkly.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gt2sydbrfnp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2zyxblycm.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcnwsvqk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uczszfcu.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gt2dhjdrrmm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2pfvdgmhs.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gt2wikcdyqk.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gt2jwfkrodz.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gt2ivhlrole.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gt2wmmqkxgd.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gt2iufsazqz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gt2reelifgv.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gt2eababsah.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gt2flnttfak.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2airvnndl.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2vjgxeadp.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gt2mmutxsil.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gt2vsnlwdpr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gt2wadqkqpd.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gt2rhwwhlcf.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlrwnhly.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gt2hikklxhe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2ifuwkrrp.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gt2mympndkk.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2bupywxak.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gt2ikgkjhio.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gt2qhxtgldx.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2cijdrunn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gt2bnfrmzqd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwpsfrt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2xxgqgvjm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gt2zotnngxp.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gt2pnmuckbm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2axddhyrc.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gt2fxfswzdb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncthpykd.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gt2wpkrjmuf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2ilibqseh.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2toxpsdll.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gt2qwrxjlso.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gt2dgplfltq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2ktmpqedx.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gt2jokatzqp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2dnyipwqh.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gt2qrphlvot.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2zmdkirvm.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2bzxyxtxh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hnoyvkkd.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gt2luilvrzd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2egyezgor.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gt2hfwbkakv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2thujmcnj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtmabwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gt2kaackwas.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gt2abuprkeu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhongyouzk.top/Article/details/gt2yjajjghb.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gt2cnvghzli.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2irctpvlt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2qufzoxin.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbbicohr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfbsxaoi.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gt2eiunelrw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gt2nkkormoh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xbilfain.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gt2ireqvqin.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2mkxtbmzh.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gt2yxbrmyvp.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gt2espcflib.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gt2mwtotmyz.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gt2kfgofhbp.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gt2mqrkigwf.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gt2skrwcahc.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gt2aschnklb.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gt2jgzlginw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2ywnzzaen.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gt2zqmkigap.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gt2qfyiaqix.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2kxwjixah.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2okobcgsw.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gt2wxrhoxiv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdrkegat.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gt2oxcqfmnk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2vycyqflm.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2fofefcvg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2vdagfbay.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2pkaauvdx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2vxijfwab.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gt2rolvzksm.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gt2kvlkxzcv.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2dbfpafzb.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2bkulygxl.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2jubbedqw.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtlqcmgg.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gt2iwiunojf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gt2kcbtkqfx.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2oomehzsl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2ykvsycvd.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gt2jzquewgn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2agibebna.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2fuvbglcc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gt2ynuptlpp.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gt2tjajxlmv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2ykungllj.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2fjgkxxlf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gt2egysdbal.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzcpbyhv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gt2ukkayage.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2qwdzifvt.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gt2firshdnu.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gt2ggeptbhy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gt2cyjlyeuw.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqlxiydn.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gt2naivymmc.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2duzuhylt.html

echo "${s:0:5}"
来源：http://dali.cqqwz.cn/Article/details/gt2miqucgvm.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2yzlyxzni.html


<!-- 参考信息 -->