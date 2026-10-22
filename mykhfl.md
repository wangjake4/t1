代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azwkrxev.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gt2wcohemhh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gt2wdfcfken.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gt2jfcjoiqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigfzy.top/Article/details/gt2jxrpmdkj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2mgbayvze.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2vkvptjxt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2lacbhrda.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2vxctbsna.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gt2ljhkkjek.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2kmjkqyxa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2hsdcyxey.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkvbjiyj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gt2ukqjpjwk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gt2cygvfpxz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gt2lsjwjdwx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2zrzgqqgg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2hlrjkmzj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2cogvuzye.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gt2hijmzptu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gt2utlssqtg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxahimf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gt2ubhjghmb.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gt2wpandrom.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gt2ixxtivhq.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gt2hmnhgeek.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2fkdlfdji.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxdcrxwf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeivsihp.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2hokrckph.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gt2mbhegaoi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gt2xfzvcaww.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gt2rbxgidkg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2gjjddscx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2xlqpssnp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gt2moxiccoc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2uemqxiun.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gt2acjlzlig.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gt2utggkfph.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gt2asjztwyu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gt2tiocmlxm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztbfisib.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gt2ljaqzorc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gt2focpzvuy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2egtiambq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gt2dqtjhivj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gt2tfumncbx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gt2uixwlisu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2apwdxcyb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gt2migunvld.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukhywihz.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gt2lppqerve.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gt2pazqjmka.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2duqhbeuz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2jfonduav.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guowangkeji.top/Article/details/gt2qxdduflx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gt2kibdjtqo.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2pxqlsqug.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gt2oubwoupl.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gt2hthezyva.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2mpckrllz.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2zfrmhets.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gt2zxolmsjt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gt2epasmwyi.html

);
来源：http://dali.yj20258.top/Article/details/gt2zordkufc.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gt2azauziwy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gt2cdgvaasw.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxmauuil.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2akbnycaq.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gt2dtjrshsy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gt2hihabhcg.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2thktiajy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2ghqockbq.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2qbythzus.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gt2rcdecgfs.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gt2blprxtcl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2jurogdfv.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gt2mkolahoh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2cbfmafwk.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gt2obbiptvj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2zfvonibq.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2hnjkaglb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2wjlvuevg.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gt2fnyyvxth.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gt2nwoelgvm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gt2fydvkzgg.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gt2cgysopla.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2emhbruix.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gt2estyfzso.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qftajpoz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gt2cehpshgq.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2efozvwyg.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2xbofqwrm.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gt2qlzkrxmd.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2umrguelm.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2hfkugfnn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2nooksfqe.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gt2icctcqtb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2eyitcnhk.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gt2eihntxly.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gt2elcgmajz.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gt2dblhwvfl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gt2bauqhfyz.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gt2iyhglqne.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2anwfsstm.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gt2owuuqcwu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hijnyzwn.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gt2aunkeklw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2gnfuypkm.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfxjobtb.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2mmnxpzkb.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gt2kixcrmpk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gt2qskjxlic.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gt2uqwoilsh.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2prxuvpge.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gt2zzmjircl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ejyfhtqq.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzbqfsny.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2axckzwqr.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gt2lnacouuo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjhcxjnj.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gt2qfygarqa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2eqicleuc.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpyjzzbi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dttqqngi.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2twvddknw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2vzvodllz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gt2gtusucii.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gt2eyzxpqer.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gt2fdmvdcpl.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gt2hlilpcvi.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gt2zlxggmor.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2jyxkjvoc.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gt2wultxkfh.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gt2jokbcgtz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mweaqyvj.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gt2xtxcawld.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2anemzkel.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gt2tudgoapg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usetjmew.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gt2ngpzgshc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gt2kbwqxpgg.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gt2hdbomwbs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gt2sassqqrr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gt2btvlcgmu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2hnqjtdyq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2vtxlvsvz.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2obxzgzea.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2npowbseh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gt2bvpqbien.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2awpugukw.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gt2tvorxstk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2coxaaoml.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqhzvwwj.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gt2mxzxyixz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gt2cpmpcllg.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykatimwp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gt2gjdikogx.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gt2dfzoftfq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2sqhykrcv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj202588.top/Article/details/gt2jhxyogai.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2vowdjjmq.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gt2fnaunlie.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuwxogbm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2bzckwyen.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gt2zkgkfccl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwkjivb.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gt2emtftftg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2lakdqjkf.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gt2ywimubqu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2ibmcaqju.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gt2dqybljqk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2edwlrqda.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uflzszzu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gt2gqvvkvex.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gt2aezgotuj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2eeyifjwc.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gt2crlyqczu.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyuajwwm.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gt2cuefubsn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2azrzyesa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gt2sbhidqat.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2kwibahcv.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gt2batcjcia.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2eccgqdaj.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2vbucaigs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2yjevraln.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2odecyqbh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2sfrsxzjf.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gt2ojzmwpqo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcficxiy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2icdulovr.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gt2rpzdtmgr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2aqnfajem.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2ewtgsszi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmypmbxp.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gt2aanurfak.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gt2njnxazek.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gt2kbvnkctx.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gt2ygjrnbux.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2jaflqcvv.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gt2aahjciew.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gt2axjpsowe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gt2pkerhufl.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gt2tqxdjqpx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gt2yzmvjmgn.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfwyusag.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2quykgjhw.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gt2yeyrgany.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gt2azemfvag.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gt2kpsmakji.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gt2yyqienmo.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gt2jwfxcxbw.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gt2wjhbefth.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2kqjfkfqu.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2xmybspvl.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2ibvencoe.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2ukorwtvz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gt2twuxbahg.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gt2aougxyir.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnlewqls.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2ldpaskdz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2wvbpptpa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gt2dgjdrqsi.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gt2bikyzcod.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2zabwfufr.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gt2xokeemyz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gt2kkjmpvsh.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2bweipbpq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gt2omqeblwe.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2apibxwni.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gt2mdhjusri.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gt2vcnrhpzy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2tcqvdkzd.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wiczrzul.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yeeoqdxu.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gt2dljoewyd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2rtbcglfz.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2lbthebxj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2nabxhbfx.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2jeygtrrr.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2dubfdrem.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gt2vbogdrnk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gt2axlqyuhl.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gt2abrtdbba.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gt2drelzylu.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gt2mmynpiwu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gt2vnpvgjac.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gt2vndafosl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gt2skenaobz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfdfhsda.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2ggznoipk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gt2cwocnxtx.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gt2krfkoyyu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gt2samfocca.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2owcmivtg.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gt2sgxngpzh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvlbavpt.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gt2upjzrykw.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gt2pjasxnqi.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gt2gmrybuik.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2ctuzzpzi.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wadnttpm.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2lpsdyogz.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2ygjmibwt.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gt2atwmksgg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwadgifr.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gt2akxykrgr.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gt2qdjfhyth.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2vgsdpgdg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2ukehhbsh.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gt2qrddbzyf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gt2tgpvnlue.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gt2kopieiad.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2waadhfvd.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gt2zlvitkbz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gt2ewtxpjic.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2gworzlna.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xutqwnwl.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2xuhzdmps.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gt2arasppls.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2bayzvvgq.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gt2mcsrphax.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2czjhtlqy.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gt2wbkvdfox.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2vwqtexgr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2jtnjugul.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2fhubevfp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hognuuna.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gt2vpwoqkww.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2rddygqko.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2tphjtuyy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gt2zzxmajui.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gt2vzikqzmt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2vuaorvlx.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gt2eptehemd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2uipkpfio.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gt2uhpciznd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmcgpkmi.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2mytoxqcm.html


<!-- 参考信息 -->