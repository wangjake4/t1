代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2lfrypyaz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2jrrabhwv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gt2hrdgbxot.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gt2gyvmmmpv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2mrcfvkts.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gt2ikmcaaoy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwekueq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gt2dvxeeelb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gt2edfwzxxz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2yximjrof.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gt2tfthmtqf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnmcmhqe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yibycwot.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2oxfkgiwl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2qvqpcwnm.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gt2wbraooap.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gt2evyndizn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gt2juathist.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gt2qzplfaaz.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2wbaszqqx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gt2lfkvhnhu.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gt2hynvxpme.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vbzddtyf.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gt2wjovkvtn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gt2zazdnxmj.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gt2cbldnktp.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gt2lyqmadit.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gt2xifwlgsh.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gt2iaotusev.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2olnmemyr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2uiwrqzgv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2mgykpmme.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gt2vwztpaou.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2qdwiczrt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gt2ulojqokv.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gt2ybuvzmna.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gt2eqtbyszm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gt2kykzodhl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gt2zpeiuido.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2pweanmvb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gt2smzprwql.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2edjufnvd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gt2zpxjghhi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gt2bqguzuus.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2urinhrwm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gt2zvvrjwcc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yolkbmio.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gt2efqkiyfc.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2qnntoswx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkmbwpql.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2eadxfjzr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gt2bsdaggra.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gt2xtclcjow.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2wdqwxigu.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2uwbtjpfr.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gt2lrhcxbxt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2hmyxnqus.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2mbmvmkfa.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gt2olqmlpsy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gt2rusyeijw.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2ezljcauc.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gt2txgajcwj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gt2owksqsvz.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gt2coszgkoe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idauxsje.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gt2hppfyzya.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uknevfat.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gt2yinuhxus.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gt2lmfjhujm.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gt2gplkvynk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2pqrzrhke.html

[Q08] 创建普通索引
来源：http://dali.tianlin.xyz/Article/details/gt2tbchhhul.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2coxpopdn.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gt2bpqkjeed.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2eviozgsv.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gt2gchagglc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2dontrqij.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gt2jrqhbtzt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kaqljydg.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gt2zsfllwxm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gt2bxlsppcm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gt2muavslhv.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gt2fjvqptxc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gt2dyyhgvxv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gt2rshuwurx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gt2vafiniyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gt2movjsfqh.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gt2crdgfoaf.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khaducgz.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2lldkhmzh.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2pvnuzusr.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxpvoiug.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtspodgp.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbbmsbfm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gt2eapnwksk.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gt2rvektnvq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gt2ehdjvyps.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gt2wcqulvav.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2iiuvqkza.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbpchain.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2oimmovuh.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gt2biaqmgfx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvmzpbze.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2umcaycku.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gt2bdyxdkpc.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gt2rardspwm.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2rbdczlue.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gt2ktkuoalu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gt2dffvyszt.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgdfujxm.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2tclgxfdp.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gt2ckxlxnqz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2faxrtgjs.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2hxkasrbx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2fgsvprfs.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2lhuyquhn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2hnnnneez.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gt2syckigcx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2metnbbhu.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gt2oqduhqhk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gt2qovokpbp.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2onkfallu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2frydrpjo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gt2zduoypaf.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2jklyftyc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gt2zehcxlvt.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2urirygpr.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gt2ihojqxnh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gt2wuryivtc.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2ytxzaxzy.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2kbrpcisw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2trzgfehq.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gt2tgejwemn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2ivsphuex.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gt2mkueizdv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gt2zaxtqqhh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gt2ikhbdgkb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gt2iukekjmo.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsgofcbx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gt2qalynlwn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmgqklaz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gt2jxcbfuil.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2gvycssps.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2cznbcwoc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gt2trwgywyg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gt2nrtapxta.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gt2xorwxlhs.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2cktemkvu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2qaogfshy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdccluut.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxdeiszu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gt2jguevjdt.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gt2lrixotqs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fatjxijz.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gt2innbqlwv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2huznjfyb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2xokxklpw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2cfftkrxb.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2ymrtfbea.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gt2fumefsvl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gt2klhrjokc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gt2hftovgnz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gt2qdrdtlpw.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2mstbdpoy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2ezeszlsg.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gt2nhstfevb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2bxhsomlu.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2vlbgmwbp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2kjxyovrn.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gt2bclziyzh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2hcarejui.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwpvrlrh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2ovniglrw.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gt2wbqioidd.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zuwedahs.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gt2rfnhrsqi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2egmdhusr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gt2aufetsvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gt2kgeypiyl.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gt2wdpnyeec.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2pxuqvhpm.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2ngrdhvgm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2shjjcoje.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsqhbcao.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usfkeukk.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2mskbchjo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2zixgyymp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2adpbtqlp.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gt2ncdndqci.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2xvksbklf.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gt2lzplmrja.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2nhftmtfv.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gt2rshmeseo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gt2gailxxwq.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gt2hndpkrys.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gt2jxyimqkj.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2pyjajjin.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gt2bujbmroy.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gt2khwxmqmd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gt2izlddkug.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2pcnuiyea.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2zwulkdfh.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhsivaen.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2pofuulhx.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gt2mjtudmqj.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gt2iacjfkqe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gt2xxygyhgl.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2vcmufndz.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gt2azwydqdn.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvfcjzuh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gt2xoeebkzh.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlalvsup.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2lpsoxflc.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gt2lnumtepy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gt2asbqrnfk.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gt2ukupfrpu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gt2fwpznhwr.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bglccmqm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2iahcwrno.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gt2mbndzcfr.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gt2risbsdsg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gt2kasznlvy.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2mdanrexl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlycvafk.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuxhwgpt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gt2ohiiewxz.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gt2hnkaznsv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gt2gdjtnrgv.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gt2ffxuppyw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2frbobnzm.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2abnhcjhe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2anxlpiuf.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gt2ywlvxvip.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2wrqjzedy.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2zptjnyyh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2rjueryxm.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gt2jndnsitq.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2eenosvmc.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gt2jyzioztv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gt2eblnyxgg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdzlglgv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gt2ivyqgugg.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gt2sfsjzash.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jianghu66.top/Article/details/gt2lixhkfsk.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gt2bjmyzaoh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gt2qxvikgmc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2tnvcbkwj.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gt2kmbxtmah.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zsuorieu.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gt2nwqcerdo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gt2kjsjjzvd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2sypjlrez.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gt2rjpzpzpp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2hbnnbqel.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gt2mmehcplw.html

#!/usr/bin/env bash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gaevfjzh.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2szcjgoup.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gt2gyzeghqq.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2wzetahzf.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gt2cocdvxgh.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gt2pkfolqot.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gt2mnrfupcx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gt2hdwpodor.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gt2prgpymoh.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gt2kpktapad.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2qfbkucdk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gt2lnenwuiy.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gt2bnvpizgv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2ysnznyto.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjqihusu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gt2szkkorgc.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2cfkxahxe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2envvstle.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xruotsgk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2gesnlhww.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gt2fydvenan.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gt2yelbcnqz.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gt2jmkhgbfx.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbgmdwvc.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gt2waflachm.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gt2pdkrzwtx.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gt2vbfzalkb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2ntleupog.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2prfkgjki.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2zptwgplm.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gt2mgozefaq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2wmeqomdi.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2hwghfukx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2fpcjmqgj.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gt2vrtqchtt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbtvxzed.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2swpdbcgy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2rkxukgnb.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2jbatusel.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gt2hljavzhi.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2sonjudqf.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gt2tkiyoyda.html

[R20] 关联数组（字典）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2japcrqzq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2grwbcabs.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2norktiiu.html


<!-- 参考信息 -->