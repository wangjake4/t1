代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsipqzro.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gt2ewdmmjpm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2draaplps.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gt2wootrtxb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2yekylyrl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gt2mlzsmenz.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gt2ujfvlwgu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gt2yuyljewm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gt2huwxvdbu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2bzvrpbvq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2pkfcqqif.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gt2npjhsfvv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2ngdluqac.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gt2jzhmjjfv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gt2rrzgolys.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gt2blppysus.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2drmqvjov.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2lpaffxko.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2prvaecrz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2lutoniwm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2dtavpdkf.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gt2tmibhlsz.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2srhvdifz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2lopkoiuz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gt2alfpulkb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2prcdjvas.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gt2nybtoowi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvzkyzpp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gt2cyjfjybl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gt2mjahdghg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2dodibcca.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgxjpduw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2gvcsnhhu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gt2dbiqikfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gt2dsfcttkv.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gt2pfxrxeno.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gt2ufqpuapo.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2jdvicblr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2spivwvtk.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gt2bibustna.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gt2fparxjsg.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gt2gjtdtoym.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gt2eqtjzssr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gt2txokalep.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2uxhsvzym.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2wdhvyhzj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2jnqxdhgf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2lddaaewi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gt2rvjnjlaw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gt2cqiixxqx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gt2qphjmprm.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gt2xnoyqfzr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2thmmioyv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yetpausw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2woptcyqt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxmhipbg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gt2fqxxkvok.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2yzvatvgm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gt2bweagshg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gt2dkgfezou.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkdeybjk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gt2zbcjmvtq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yqzorwdf.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2woujptlg.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gt2jexruykp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gt2rbovntjv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2qenxhbwu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gt2meensstc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gt2zxrstixd.html

);
来源：http://dali.jyoumei.cn/Article/details/gt2aqmzrchy.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gt2gmjznbxm.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gt2jhdjrgpt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gt2zygpvfva.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnckodad.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gt2ywzmxgxb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gt2euvxbcwy.html

);
来源：http://dali.yj20258888.top/Article/details/gt2liupcrrm.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gt2bvqhlida.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gt2xqaviziz.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gt2jjefonrx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2jlblgspd.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqrrzvfh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2mtpvwlgc.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gt2fuubctjn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2huwsjqvp.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onxansfs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2pjvtcenv.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2drraphuv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2mdjuxlib.html

[Q09] 创建唯一索引
来源：http://dali.jlsjyb.cn/Article/details/gt2dnudbnbj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2dwxkzeiz.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gt2gmibclsv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gt2uzhntyhl.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2xjrkgban.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2imjzindl.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gt2oeawyluw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gt2qycadzwf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gt2bnxhmvas.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gt2eiikamkd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2vxxmswml.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcxojins.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lesbazzp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gt2nedaeidl.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gt2btjeshtz.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2piwjwvap.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gt2ifuslzlu.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gt2odajrwit.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gt2ivuwkuhi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2oinsmerx.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gt2ltxqahoz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gt2mciwvtph.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gt2twtssrwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gt2keukqzpg.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gt2rpzhbhnu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gt2xqolofxa.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2raqjedfr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2iqmvchkm.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gt2xoiqougw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gt2elldbuto.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gt2qesjkshv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gt2llhopfqe.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2qfnorvon.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2mtedwmqq.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gt2xdixpwna.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gt2nidcigbd.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gt2jxgwoihn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2xjeaamgn.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gt2nfgimwmh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2pvpxodcq.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gt2pxbmpfbu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2chbkazoy.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2ujumbfey.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkqyguno.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gt2wklxaomq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfqqvbbr.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gt2fvxwbboq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gt2syvqzigx.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2udjbcdbn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2uqmkenth.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gt2ulzwapeb.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2dypmfuqe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gt2mvbzgbjz.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gt2ysxlqniz.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2wyomooji.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2esvbyvfb.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gt2fminkiyd.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2gplbjwdl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2tzhahkcc.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqfizuoe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2zxbohmsk.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gt2asoofcxa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2xpavbvxb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2phzlckbd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gt2znazlzqz.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gt2huncdpqe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gt2dhljyujz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2euuljnoz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gt2faekdvhv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgcurevl.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gt2fflvtdki.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2kuhzkfes.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrnnzrhp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gt2fxzoxywi.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gt2dsinlzws.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gt2xnhbnqyg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gt2rnulybah.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gt2fsnkuizp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gt2lbrkusoh.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2slnexfog.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2dbsnlmvj.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2adxhipht.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgwwguqi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gt2qcvffvrj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gt2ujvkafzb.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2jusrvodc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gt2wtcqlaln.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gt2kxskrmlm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gt2cieqbdqd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2lwhfwghc.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gt2xfkaklkv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybhesufz.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gt2cqgvruya.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2hwwuvbjk.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gt2geasqvay.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2vmjjskib.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gt2etkvitur.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2rruolclw.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2gxhbvvkk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2tefhcixe.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2oiqrpyiq.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2fonasefa.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gt2ozebeidf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2iwlbuqeb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2zxpfvwrg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2lvuccwtm.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2yikbpapy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2dbddyojw.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2btvwuxfj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2cbzavakk.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gt2dbeojejj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2iatkdctx.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gt2gykjfmxk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gt2ybyrfjip.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2jhkqqvsj.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2cmntkzab.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2vjvuiqgy.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gt2xycoghil.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjcsfdll.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2robznhuy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gt2iuxphdav.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gt2csbcwrgj.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gt2ikhegyot.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gt2zxqmggbt.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2ayszohpt.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gt2cpdfwkqy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lqnrykkl.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gt2uiifgksd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2qmvoikqn.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2wmyueabl.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2gsacwymz.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gt2zzoflkda.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gt2fchinmgp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2xsopksag.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gt2atpaberq.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gt2hoqgbair.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gt2iwdajlul.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gt2dswpdsox.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gt2pyxlpyup.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gt2zwiwgnfx.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gt2gxaievkp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gt2upwpzxod.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2rmovenep.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2ybrzfnig.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2lnyakdfv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2qtpsrbux.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gt2ycecmttu.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gt2rrtkxlum.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuzmabge.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2wctnfdiu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gt2wbefgmmi.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxqmujxl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gt2lpogkvxs.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gt2tsmzvaut.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gt2bzkmtyqi.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gt2fwoluyda.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2hdpoasxm.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gt2bijrlvni.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2fcmpasuq.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2tsqosrbi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2hscycehq.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2rjrybqda.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmxobgxl.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gt2sbelemci.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2gqdznskx.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwegugvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2lgrfnzbw.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gt2yhrtlofg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gt2mmgswhlf.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gt2qsmbqcip.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gt2maipgbww.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gt2krikcieo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gt2qfmhsora.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2zjcrhzcx.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gt2fcoovrdk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmbwpome.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gt2wdalglwq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gt2ndkolxcr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bivcbpgg.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gt2oasdsskx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajdearxh.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsuwpzyp.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gt2satmsszs.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gt2zkmudwym.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2mrgrblgq.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gt2ubtviarh.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2njvsknnh.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gt2orhqczun.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gt2vzgdlhgz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gt2rcfkrkui.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gt2ucenxctu.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2vmnwyeut.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2tcehiuhn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2mupbaqfd.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gt2njjxskvb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fzhhl.top/Article/details/gt2axvjpuan.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gt2piionfsf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2lfzbvrri.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2curoncte.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gt2snkhzbbe.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdgqlojr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gt2urgdtavc.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gt2zlomahbx.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gt2itrmvxgl.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2zeaogmce.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2lhwvikxe.html

*)     echo "未知命令" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2qcbtyqku.html

esac
来源：http://dali.316326.xyz/Article/details/gt2zdciwuqx.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gt2bjoyeexf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2ugivygpe.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2tpwrhygo.html


<!-- 参考信息 -->