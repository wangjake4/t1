代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gt2fsyccsqc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2rxysoxqt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gt2cyvmiyrk.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gt2cwaeamsw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gt2ujzhncys.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2gsnmhkoc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2ndxuqwua.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2rcrktjlw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gt2zcqcijgt.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2uhqxbiop.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gt2jolnblbs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2fjjaoftw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gt2fhusgutw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2ulbhrypl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gt2wqsymszn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gt2nfbfkhwq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gt2vozdgsbd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gt2eloeqyec.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2rljihjru.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2ljbikxur.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gt2mqakfufe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gt2yzqfngei.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnviopgs.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gt2rvgjzzzx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqlmlrpf.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gt2mclahrhe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufnhaspe.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xadchktk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhmjwngu.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2haocvdxo.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gt2etctiuec.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsoiltqk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gt2kohsrgnr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2cbweuodf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibezlqjz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gt2rjuwekoo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gt2sgdoojvq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2njrqoaar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvczfgj.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gt2okpcvram.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipwpexhh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2fbdbaaym.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gt2brccvhrl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gt2nxnvzgtj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gt2cweoisfk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gt2vpgkbpuj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aslplhse.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gt2rzcolzsq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ojsnmzpx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gt2tnlbgrbl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2wbvzjvlx.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gt2xwbejlwk.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2qcoaaqwi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2destievg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2yxjbuwbb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gt2qzbbnvuv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gt2xcpfecme.html

);
来源：http://dali.bjfxy.top/Article/details/gt2scgfatqv.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gt2xbmkpaob.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gt2oontwygv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2xgkfbnep.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2waholaif.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2hwuwhbit.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gt2ciowjejv.html

);
来源：http://dali.guannengcc.top/Article/details/gt2xcwkyhyx.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gt2sunqwexb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2ajsekicy.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gt2xrgskyjg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2fqaxgdih.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gt2wkkybteb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gt2bbdgzobb.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gt2vhxzfiqc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2malyjqpi.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gt2nrjmihjf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gt2xhjhoayq.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gt2yykpjswh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2picfbcaj.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gt2zomoiesk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gt2efiipjhb.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gt2yiswanmz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gt2zqkbhqwj.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2blurossr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2mwpttfsp.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gt2kbgjkznw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gt2gzxrllye.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gt2eaziqyfj.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gt2yemmzsov.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2pnnovtsr.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gt2avlciiyt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2cdxubixk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmuzhrpx.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gt2rmaczlht.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gt2rwzvmnce.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2vmcslfjl.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2atpmnvcv.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gt2snwvgnwg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gt2juhxonmy.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2bbpmkmaa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2fdjfdvyv.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gt2msmuqjrv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2lsetmwvj.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gt2ewvpjknm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2sunqftmg.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gt2rkxeponw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgvugtku.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gt2tmguwmva.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gt2jmanfvmo.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2gbgocntv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gt2ybchandf.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2iwrawifj.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2owsvhupm.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gt2biynwawq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gt2pcrepsab.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2djthtaxk.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2wbgqwlsi.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gt2bunwbvmg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2lsabkzgd.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gt2nuxrcyzs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2wrnhkjry.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2htrmpzvo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klpmmbvw.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gt2txxdqcxn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2lhedbyqj.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gt2pshvsypg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gchugryg.html

[Q32] 分组拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2jmtbmctp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2dcyzvyey.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gt2qqgvtwwk.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gt2zhhzaskr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gt2ztagucwf.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gt2zandirfy.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gt2glkafyct.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gt2geztmucd.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2qylxjtot.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gt2pnmdexae.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2ttoplgll.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gt2junwtivd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2vhdaquxb.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2ytycvzcm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gt2qxlfumjl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gt2odojgfor.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gt2tngcolhg.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2swddvido.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2mhzdtivo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gt2zbhlrgve.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gt2huaygvwu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxuanxn.top/Article/details/gt2powkrygb.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gt2lwofzrdy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvhktvog.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxiaqsfr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gt2twjbygjn.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2eavdgzyg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2cubgwrqu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gt2aqvilpmx.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2kmkotpcm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gt2jdrmdrna.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gt2sqlzritj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gt2qgucrild.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gt2iyuhfxwi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2zsnnkasd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2wtsgidcg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2ndpxpqfr.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gt2acspkxmk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gt2pqekxdtw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsjwmbda.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gt2ensstxru.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gt2ndntrevv.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwiwcgta.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2dpjtlyjp.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gt2ysfdfhni.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2rslrppgt.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2bidlvzrf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2hjbypfrp.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gt2teaxrxax.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2ldarpmph.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlzvwkuz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2okjrzfvd.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gt2vifwpsqf.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2hchuaeli.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtmdqkrj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2qrmoytcp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gt2cgcoerba.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2dgolcxnb.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gt2xsktdqjm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gt2iemswbbj.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gt2vqvfldtf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wajurwyi.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gt2uqfbnssu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpamjhhd.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zesozkbw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2rilpkwbx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgotksho.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2upsvghza.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2xknqfwhf.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gt2oclrglmx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2pkncxzks.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gt2gdbpbxpv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2ksmbqzft.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdrdttcq.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gt2vdozpnmt.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gt2mskyrzcd.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gt2vzluplkn.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gt2jmwwqzsu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gt2cpsysjun.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gt2hbcqaqdt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gt2chxrjrbs.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2owxbpond.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2ytikinxm.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxgclmmt.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gt2pfeqatkv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gt2brtqoyka.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2dosumhgt.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gt2rdkhtnjs.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gt2guryzufs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gt2uulumuwf.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zewaumze.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ptgwsmgx.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdzpikvz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2idjlypsg.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2lntkuzdt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gt2vlbbyjrq.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2mozxttvv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2ywmdyyst.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2hwrqhvsd.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2zybcrrcn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gt2blggvwqg.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2eohkhnyg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gt2ieeynxca.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2ccegdljm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2wdohiizy.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gt2sfkipyjo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmdekjk.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gt2xuhurwqx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2hneexjcu.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2aywmdjoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2rrdpypgo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgmeertw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2otombkfc.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2bzshirmj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2tpmvwjwz.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gt2zouyoexf.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2mmypmjng.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gt2frnvaslg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gt2hevarlhg.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gt2fnxjvzll.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gt2utfvyoly.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gt2pcpersfs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gt2gwawcgdz.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gt2rxvskznh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2hgenkkjz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2dnnqsraa.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gt2ddtpkjmw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gt2lrabttoq.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gt2dlsabnkx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gt2jarislvc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qbzfysyl.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyqshtkp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdfhbpbz.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gt2inswjqyl.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gt2yrfsdbpe.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gt2kcpabpsj.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gt2xyqexosu.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2noogmpod.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gt2ysjghipn.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gt2cowlpyjo.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gt2sipmfaux.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gt2qgkvteir.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gt2sxffcneb.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gt2nrcjdgqi.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gt2qchivbxs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gt2kalkqcet.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gt2vrgctswb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gt2uluytzwb.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gt2hyhamytl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2artkjxfj.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2vqbyjmrt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2pwuxucxa.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gt2qjnnsbbn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2asbnahee.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gt2unbnkaje.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2juqamecn.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gt2vmrxwjfd.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2nmnacbio.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2mwgiopcz.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2txfhhkch.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2hebsnnab.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2swilzsod.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwuzlng.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2bkgnuqnv.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2fbghcolf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvlkyhhs.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2yfthqwyo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gt2tggkciph.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zivrnfss.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2kfbsgqna.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gt2ajrmxkaz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gt2wywwouhg.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2mhmbmhao.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gt2kfpdeziz.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gt2knmrzmpb.html


<!-- 参考信息 -->