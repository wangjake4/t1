代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gt2vbkrlznu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2gatfkqte.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gt2ktzbjiyw.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddlonlvr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gt2hecfoivs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2vycehlqp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2uzcnpxwk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2wrkqigvc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2awgoydaq.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gt2dcofvxch.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gt2zzvsprkp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2nytdzeiy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gt2nxlkgwvp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2cbxllnaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gt2lmpyxwgv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2bzxbnjky.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2aadjqaxr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gt2fqxnrddf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2tosxmphj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhsiihd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2dvxzsxvp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gt2domcucug.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gt2paibhvsu.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2pevyrvqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gt2yoziotwy.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2bfvihwns.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugfzjtqo.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gt2sbdozhlc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gt2dzgozkjl.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2zegitfqq.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gt2clajkjdf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxvuyxor.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gt2rnitatdd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2nczajdep.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2ppupxutp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ifbajdwf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxvcsspf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2igmjgltb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gt2gefitaau.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2fhonrnmk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpvqqfzk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gt2actvmgew.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gt2acqzanei.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2mmollvaz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2dzkuurtf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gt2fzdygyzl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gt2kvpuiumz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gt2wevanizr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2jlupphwf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gt2lhjvvxrb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2mhpolcmw.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gt2syvqakjz.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2ympdqutk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gt2ramvirya.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2uvsyouhl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gt2ixtwscyu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2qcecrkdv.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2soyjkcti.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gt2xupwfczh.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gt2nrmgceyq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2uybcwkgw.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2lhoxzgcl.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gt2wyhhyseb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebhmwfxq.html

);
来源：http://dali.nwbrower.top/Article/details/gt2esgjqnen.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2ypnsxtmj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gt2siyfzkcr.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gt2hzldajff.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gt2xhulmhdz.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gt2oyfrhdzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gt2zenekwnb.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gt2ovnkynqs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gt2gbjqlvlb.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gt2qdmnlsys.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfqfuzla.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gt2nafoxucy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2ttecrwfm.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gt2atbgrquz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2otenabmb.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gt2qvomvwve.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2krdutcky.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gt2ugtxvoab.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gt2qukkaxel.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2orwkpvaz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gt2itnjvsgw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gt2ekirdgqu.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gt2qsjnmblb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2jqmjmkzb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gt2lowagoau.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gt2ultafsjh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gt2xsmtsfyt.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yohkfjtr.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2qoikokix.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gt2xgfcovdg.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2iyedfggh.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gt2gyrchlgk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yevvemzc.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2rmjglwfc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxvvjucw.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gt2fjatjpgb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gt2dyejhibj.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gt2klsqfpqm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gt2cemmczsh.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gt2zbciclid.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2mmebondq.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gt2imnupbnz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gt2dqmvtaba.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gt2bvqhutpr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gt2kjnlditd.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gt2ltlfkgws.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2dojivfow.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gt2rmgmgaco.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gt2lmqejptu.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2loxxuqsg.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2wruucifi.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvbmjjub.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2joevtphv.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gt2zipliakx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2pcwbfcqm.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gt2rtsvkmas.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwukegbw.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2riuispma.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arsadjfj.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2bleggnae.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnzoyriv.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnywuhvb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2ybdxrwkw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2nzptqvgh.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gt2ebhjkbvk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gt2btizednn.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gt2kwjggqts.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2sjqhkipc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2plrrxbzd.html

) t WHERE rn = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2bzllkabj.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gt2qtmuprlq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gt2vvamyhkd.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2bobpviad.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2vhlxrmqb.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gt2cuargrfw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2txlwxjgd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdprcvsl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gt2wwlcryeo.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gt2trvusxbi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gt2aeskyfdy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2kvfvxkbu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gt2apdivfob.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gt2fltobfpc.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2huwaardd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gt2pujtbjlb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gt2epeegjxl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2bsyznqid.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gt2ucxwhmzb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gt2trvagova.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.mhx1999.top/Article/details/gt2fcgpirtz.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhesgpha.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2opnnymtb.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gt2vvanvfmz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gt2hisriznn.html

[Q45] EXISTS 判断存在
来源：http://dali.quarkkingdee.top/Article/details/gt2cwxajnhq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2deinzbhg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gt2bvenwude.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qacpisvv.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gt2dozafwvl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2junwkgim.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gt2sxrxvmvf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gt2ourvdezu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gt2akdyeseu.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gt2knhiljfh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2keoaamrp.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gt2fgagjlzc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2ftawvnlx.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2dnllvcdb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2qlbmfomu.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gt2lygvsecm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2agrnovcy.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gt2phhgbdga.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esmylvds.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gt2uwklrjdx.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2vexufuzs.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qiibbakr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2cnxpauzf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2tjywbxax.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gt2egeuwhne.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gt2ivwiyqms.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2scdmvwoi.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gt2rtcvesnk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqaykmgy.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gt2iifmcflq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2nwofwowf.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gt2tgdczwwq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gt2sbkvapnt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2pmqkazrh.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gt2jpacidbt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2gykrtots.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gt2bfpncurc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2ofivczxv.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gt2dtegcohs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gt2hfscqxnb.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gt2mezhxykp.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gt2ixydhfqj.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcmjsbnd.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gt2vqgbycty.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gt2patiphzz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2eukaujrg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlhgdun.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gt2smiyhqky.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gt2wvguucho.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmhsrhje.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2ebvqggoi.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqjqowmn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gt2tizzzcgc.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gt2pilvooqi.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2yoytmjbd.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gt2bywrvwek.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxvehept.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gt2qefpttcn.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2wzjlfwif.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2hixnwvop.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gt2sumcnqlg.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nezklrhk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2korewdfo.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2bjgqzibe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2wdoyvcxs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gt2fmkiyaej.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gt2tkbioohm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gt2vsmuiujb.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gt2dqftgrhw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gt2rbhcrlat.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gt2wbjnbwpq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gt2xgqopwkt.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2ntntyvmd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bplpwnjq.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gt2dksnapri.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2vpqmzkim.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2dqkucnoj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2eosqyqdg.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gt2vaftwtrv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2jjepcafz.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2oollachy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2baizyiym.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gt2roogeyik.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2punvfval.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gt2cziqfkig.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2zzlrzaqq.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gt2guqehojb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gt2gpskclqo.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2dszkpejj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gt2bjpehirz.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2oytledmx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gt2hmzyvnnt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jrfexkqj.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2hwndbyad.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gt2jchyvhqe.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gt2ngpfhnzd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gt2gmevdrmv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2svxcbfdz.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2hursvtuz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2oedhamxk.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gt2ryppzchg.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gt2zdzahqcq.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gt2lhbxylcx.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gt2eremiwsm.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gt2vbwodtvs.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gt2mvblbxbv.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gt2kcdbvwck.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gt2bgowqcyj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gt2wjxidpop.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybbtiupl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmphuwpb.html

[R06] 判断命令是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjcxdwqd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aftnnjvv.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gt2imbdparo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2sorpclil.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2zazhxxay.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2gnrurloh.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2bshfurtm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gt2uitmxuak.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gt2pgyacruk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwbzumth.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gt2jsvdqukf.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yalsbhcr.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2ozjltwch.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2vjwqoqcb.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2vznnjagk.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2kmpeyacx.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gt2ozcnqitb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gt2jyuricey.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gt2zqovfjda.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2yssslqbk.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gt2tcnxfsgt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gt2olqwrzrb.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2szvtxrco.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgugkxcv.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gt2xzjpoujs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2pizygdhf.html

[R17] 数组定义与取值
来源：http://dali.zhixingplan.top/Article/details/gt2hudtfwzj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gt2blvdlozr.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2izjfzwkf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2oeixmvwk.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2gfyjxwyp.html


<!-- 参考信息 -->