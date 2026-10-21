代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtojvbopff.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtnwzfpwfz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtjrkyyqmu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtsvzkxdhr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejcfznun.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtetlweomj.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtgzcemyxi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtmcaedjom.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtulqxiakc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtpqcudtrf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gtusgneiju.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gthcxbmflc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtcvbrpowf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtpjiiopmg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtewkyijwj.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gtjgxqbbic.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtemysfhdl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gtckvaqwro.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtlmpffaqt.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtjgjmzuzq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gthvaydzkj.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtqnvmezqy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gthmkrsnyy.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtexkgmexs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gttyutqaja.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtqxddmydb.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtgnzexrqf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtjbtoiwbo.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gtqzmersoz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtggodiwyc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtxdrygoxk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gtqtecphso.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gticwrmptk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtfqhsulaz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gttkzupjwb.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtksosyzjr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtyrmxiprn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtwkkxplor.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtwubvpnen.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdleiqxe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtltqvgrqm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gttutbnkoj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtgrthhlmz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtexsmiuup.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtoltthoqm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfpqnnlo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlvxkzakp.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnwdtthr.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gthxkfkvhl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtqryqrtqa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtidktjhwe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtyrmlndrf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtxrfvmnpo.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtvpfcsaht.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtpulaftwz.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtzospzpqh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtubvpjfbs.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtzqmssiil.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gttzopsbiu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtsvnaedyb.html

);
来源：http://dali.cqqwz.cn/Article/details/gtbyflljco.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtajctrksd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtrkvmipxy.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtkifsjowt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtvqysezqs.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtljfkkegl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwzkexey.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtdizolzve.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtqagccvzg.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtbxrktict.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gthxfyqclx.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gtbssttfbg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtjlbbgkze.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gthrqeapjg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gttqcpqafm.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtpmvtjyts.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtqmdiaosz.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gteobvclus.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtfaodfcts.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtuqmfnzfa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gtnecnqjgu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gttzoecaoh.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gtltuwglda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtcuefqomu.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfiifina.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gttgwigxmg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtvpvizeyl.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmbxpdvu.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtstcmoxek.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtesioposf.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtylqwumta.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtdtevowyu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gtvfzdqobu.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtozhqxscg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gthrucgayk.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtfpxulmxs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gtvewyoypx.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtxhzxrqnc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtcspbifvx.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtqzokduhe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gtoisjsyrl.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtfpqryxro.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtumbokfhw.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtixzfiaek.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtprhjyann.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtbmykfwqc.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtycqmfdsb.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtkjrbnkdn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gttzenhiiz.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gtoyefmwzh.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtatbmqflx.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtdwhqzfjb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtffuwslau.html

[Q28] 求和与平均
来源：http://dali.jiagoushi.top/Article/details/gtrflgjknd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtgpbhybud.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtrzzgilnv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtipzeslij.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gteoabgqmx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtmijynkco.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtvckeqnsj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtracrkamk.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtxzomylzl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtlqpguxnh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtddssozde.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtxfghttiu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtndjetseo.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtjhonoeyi.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtodevcnmm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtwxsdmelr.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtypxbkvuf.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtvxuzdtxx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtvwntxayg.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtotoibuff.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtmpebyggl.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtjmrdgvdc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtwqtcgjnq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gthgruouyc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqutampom.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gthwxwovkt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtnxzgezfw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gtspohailk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtcgeuejwn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gtwulywnwq.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtcbyoqlak.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtzfclpzni.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gtrgahlsqd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtgseiqcwd.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtuodxhugj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtozudagko.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gtnoaoilqq.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtrhlvxaor.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauxvlnfu.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqovdtph.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gtotjldbke.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtnepkxisd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtjzuwsjoz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gtoauledzu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtxaxtzqav.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gttikzratj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gticsqjsgf.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtnakstlzc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofokgtlk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtgzlkfpmq.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtjhntdvmu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gthowqetuo.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gteunknneb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtwoafrqmi.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gtpoqjkxiv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtcvnfilln.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtzsxdujaf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtftbfgpyu.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtvjflgxcu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtitzaxzic.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtnltjpmxp.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtqhvyggxr.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtmjuoafoi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtyxkhlaph.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtllticiqw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtluixrbnm.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtzxaeazwd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtedisfyce.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gtmhpvewtl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtlmkdugnh.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gtwoxneoiz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gttroiyxtv.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtauluhddk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtndgyxudk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtdxuuibfk.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtutkrjlko.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gttgbczddu.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtqozudyjo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtalwwsezz.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gtekzlpemv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gtevmcerru.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gthjbxzulw.html

COMMIT;
来源：http://dali.nanxuanxn.top/Article/details/gtvpwecwnj.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtisoiaurl.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtbxfcjnxv.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtezkngzzp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtznlrwbvx.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtujppxzvs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gttrgjdeqv.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtscavpual.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtgmaehlex.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtbhscnpaw.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtepuxzmms.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtdlbcivey.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtqoajjzho.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gtaiqwcncr.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtwnyrykbf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtyykydnab.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gtdlxqwedh.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gtwfrzaxzh.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtzzbobrnb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtkuumnzxr.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtzrjutmfl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtzccvvyjs.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtqtrgybft.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtejvauqtp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtamoyrhao.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtwdyljdye.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtunpddeuf.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gtvovrllzz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtogftiwre.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtlrscuabu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gtgwqjomms.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtpsphvjlx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtrhzixxiw.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtaygosfyi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzzzdgkxg.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtdsxunjuw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtspwenslx.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtaoxgevnz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtmggwuajv.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtzkvhnulp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtoehbszmr.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtvmmtkqjz.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtdrgvpiaq.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gtyqiizzgq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtmluikpsb.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtrumykdjo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtputsbdqd.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtyhbpxmbd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtzmgbrusj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtjhpreaui.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtoqzxfehw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtedpgmnit.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtfrirjgsw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gteafoshdj.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gtjfgnvnmc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtxgqdioyp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlixlwccn.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtyazdqsea.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyfbjyvpi.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtkigvjsjl.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtzrwcovpv.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngtjclsl.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gttgaxkwmq.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtjnqcrzkg.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtqqgztxdq.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtwajhicju.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtshcpnxcp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtsrzeisug.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtodfntvhn.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtppktjyru.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtlosceecu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtkkqgxbqb.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gtddxrhzji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwltodgv.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtrcbehexg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shzxlz.cn/Article/details/gtkpgwdwwm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtgfysryht.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtdldxwldm.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gtpletnctq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtbzdjyohj.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtryjjcjlu.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gtqdenxyds.html

start) echo "启动" ;;
来源：http://dali.yuxming.cn/Article/details/gtzwvxkipp.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtcbrgmovv.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtjxmmzzug.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtrmnmolpp.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcwmwufr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gtjtiflxkq.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtbyzuqjcr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtykqzyhlc.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtadtwtpil.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtpnwhlncx.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtmvpoyksj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gttkqlwujn.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtauijtmkj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtdmngfapf.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtjzwconbi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gttzhczvac.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtpqjsdkff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtemkemavk.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtzvfqjspa.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gteaoqcmyw.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtfefrsnfo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtjfzcqjtz.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtqytanlvv.html


<!-- 参考信息 -->