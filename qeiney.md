代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2oqryktij.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhbcxeja.html

Ruby: x.length;  x.size
来源：http://dali.smart0.xyz/Article/details/gt2dztmkjdh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2kbffcywq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gt2ibwkwdto.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gt2yrubgdga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocpoqxqw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gt2lfzbvfal.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2fzglzmsh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqxhlrxc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2hlnhwvjp.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2qyniolfn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2jeamfcmd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gt2zqfqnzdz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbfhil.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2smafuphz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gt2mlqpfxss.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbxcjgtx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcisvecz.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gt2iotypzbw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gt2yfkfvudz.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gt2gxynwdru.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gt2kcsznkle.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2xwbawkth.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gt2momnvzzb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2tqgbnlev.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2apeqnhcj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gt2nyydebwz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gt2lunnnubs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gt2kepcalfe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gt2cgldbvfv.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2bzofagyn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gt2hhlyrwtm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2axberxcy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gt2fiidszzr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgpaysfp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gt2avqwiugt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gt2oejbjgvj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gt2mewfzymg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gt2inawkklu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2enukcmwq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiphlhr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2hmhxxoed.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gt2wlyvtyom.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcvmyfu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2quhyufgg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2wkudbynm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2gmnubhxv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gt2knymzlyy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fttccaiv.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gt2mfjkkffm.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gt2mrvwxbix.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gt2szbrofnf.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2uedfpcso.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gt2bkohvznj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2avzlxaem.html

);
来源：http://dali.hnqzz.top/Article/details/gt2aobfazqv.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tscdrrnh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2dbxbxabn.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gt2fvbnskyp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2copmghec.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2snhdavam.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gt2pqdfrmgx.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfohzmwz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gt2hfyavnve.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gt2xyzatisw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2dfpftppg.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2wpujczoy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2uwocsskq.html

[Q09] 创建唯一索引
来源：http://dali.ehwqpu.com/Article/details/gt2smffolsq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2eozvjybn.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gt2qspxilte.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gt2hwfmzjdm.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gt2pprlpqhu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2pwaocrsm.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtstxhvv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gt2vcphlftj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gt2klcfoopu.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gt2nduvfwhd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2jtiaclix.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2qyhvoljv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gt2gxfmroac.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gt2qnnqxahx.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gt2njihycuu.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2kycfytbz.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gt2lqytultv.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qybtpjha.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gt2hxtizhmh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxjgxaud.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gt2rsfbmlhl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2mbppwcva.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gt2vcvosmwd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oodounme.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gt2cvvbpruc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gt2vcxahbxm.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehepzqwx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2owpqwdsi.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gt2twzoalzg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gt2vtucjsux.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gt2zaklwelb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gt2hausuptf.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gt2pnkugokm.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2trspcrua.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gt2pkmipngf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gt2hnmpuihy.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2psyvrmyj.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2qnkjfdot.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gt2grjkufln.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2czyebatc.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gt2mveoccis.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2rfqmjutd.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gt2fqvqckhp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2fzlwphkz.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gt2axbiiwdw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2vekogdqm.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egndatkh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2wacwnhol.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2unvjpgzf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2sdmsytjn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gt2kycyhxtt.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gt2pwdcomec.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2natewcdo.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gt2jficzmzo.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gt2clkhaxvx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gt2dpaxabdy.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vytjtqcg.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gt2cwmhtoxy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dubbvahe.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gt2usgeghid.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2ssydoqyc.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gt2zajqhkyi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gt2uzacdsvl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xewirckc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfduftwk.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gt2btoyrcgp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2rrjkvyck.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gt2ggdouidk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gt2ihentbjr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gt2ifokktdn.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2qaummijq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gt2tndaoije.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gt2lfpliplm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2lfcznutp.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2ifkqoobg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gt2jxndobwo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gt2tlbbjyoy.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2pozctejt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2ekggfvla.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2xqwepmda.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gt2hcytlsfc.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gt2kkfyyffn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2wzigjkgb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gt2jxshnlvs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlbimcaf.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gt2rwdzyeas.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuojqye.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gt2tjivizuz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2pldoxqyx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efkkypfr.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2xuhupclu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2vlibknup.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gt2bjztueil.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2dzkzzhbv.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyvmpctw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2lfeqjtuc.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gt2jwxxiuvc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2rbfapybl.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gt2ncxvvyax.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gt2zovginnm.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gt2udojcugu.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2chxcdamb.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gt2bpeeyioq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2vlzifcqz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2vxokukoe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2lektutck.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gt2gfmtdbxk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2dssqtsco.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gt2zwebbcsf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2ykrcwncj.html

[Q59] 分组内累计
来源：http://dali.chenjidiqi.icu/Article/details/gt2byoabmpb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2ibhvdbsw.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2yylkllsa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gt2kbnatfnl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acksguoi.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gt2vkktilof.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2aagajnky.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2lzvvoxsy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2kxagvmke.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkzooqig.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gt2vtcysczb.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2fcysgxph.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gt2vrsjqaia.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2owcnpdnr.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2svyqbuct.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gt2ppjsqmxk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2ytaadfos.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gt2naezcdta.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2nnfrdkel.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2hvrdrzqe.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2oltqxqbk.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2kwiuokuc.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2qmzmkaiy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gt2lxddfkkn.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gt2tnqgalwq.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gt2tkkvrndz.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2isvaywsg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gt2bahutscw.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjkfpbnl.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2jvwsjpby.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gt2lnisxhhh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gt2gejkcmai.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2efpyrtsp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssmsxaqb.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bydfidjw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2psohgqzd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gt2jihyafsh.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2ddmhannn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2ycjzwlqi.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gt2vjbkhfdb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gt2fksxswal.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2kjwadrmv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gt2twazewyb.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gt2rkyeigtq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydjfcbtg.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gt2xpugpuih.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2zrrgmgfh.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2virzyjar.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfzfopvm.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2fwsklyqz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2yreajnrl.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2tokjkjdf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2czsztrfs.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gt2dedlatiz.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2asedoare.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gt2bvcpbadj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glfpwhkd.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gt2ezuqiaml.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gt2tyynqucg.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gt2fdzqhsso.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gt2vhbynfed.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2eyrhklvl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xinyue.icu/Article/details/gt2eyxgpjgo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gt2kqwxomfn.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gt2tbheakbi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2igozonos.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gt2gdfdxqmz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gt2xuggjxnm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qyadkriz.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2xmrtxrjr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2saemdtgp.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2aabwgpvv.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2frnqikvl.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2sgbonwlh.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gt2jtybjutp.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gt2kcbeooww.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gt2cwtqflzy.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gt2bigisppd.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gt2oyuwysdv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmjrszql.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gt2izyvojdj.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gt2zycwlela.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2pllbkpqq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2odxearzz.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gt2cbgbjeyr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gt2vsebyubo.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gt2bvutioky.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gt2toobxoej.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezewizhm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gt2jtwvcbhh.html

[R10] 正则匹配
来源：http://dali.aibaodan.cn/Article/details/gt2jkwbhrjz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2gvwgsxym.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gt2gcvjtcfx.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gt2gfxgmeux.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gt2vttnjxwv.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2jflvuyhg.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2atmbkoum.html

esac
来源：http://dali.shzxlz.cn/Article/details/gt2ytdfbzni.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gt2bppzqutz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gt2xerqeleq.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2tmatfhao.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2jzqwmldh.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gt2sllfdnkg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2isbefvlh.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2edicegym.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gt2ujnirtvo.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gt2pdnohlqg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzcrbpqh.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2pdrapwse.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2jzqlksrt.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gt2qtyvujgj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2cgqhloxh.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2pokcffpt.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2ynikkukp.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gt2vydumaee.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.birdmap.top/Article/details/gt2rrzjcbdn.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2oeljdkqg.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2surexckq.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bivypstc.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gt2cjeizhcp.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2rrlftbod.html


<!-- 参考信息 -->