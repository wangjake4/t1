代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gt2lbhcmuem.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gt2udxztyfj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgnciqks.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gt2poedktwb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gt2idobcovo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2ubcjhtgu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2qsjrnyar.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2ixvlgecb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2orxdobnx.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2hyeiwrby.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gt2pmnlkfct.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gt2iokoskze.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gt2mniamudc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gt2kbndrqta.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gt2clvpppfs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gt2loryraxu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gt2uwzvfern.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gt2gkxphgsd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2dvndynhv.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juwvqvwi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gt2lnwqgmkj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2bhjytxuu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gt2nupfkffe.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2tveqiuys.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gt2gypykqqc.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2fnixsoqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2nlekdvrr.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gt2ldbhhoor.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gt2doejuzxm.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2xdtjmddw.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjpxtzqe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gt2asaggyzk.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdgunqbk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2azevisjr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2arcskxxl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gt2fxbqanzm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gt2oestidhh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gt2zmsnarji.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzrjzkyf.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gt2dojzvksb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gt2uviqwzwt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fogeguaq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2sqfrbzxf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2emodcxym.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2luhfdntg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gt2uquyndfy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2euqiiute.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gt2msflrpgq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2velitisj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2mnqerwee.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2dhopaqpt.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gt2driytraf.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gt2zilnspiu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2tnosajhf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gt2vmjbuqho.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gt2gecbdbxv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gt2gibrznlt.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2uxynfdtw.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gt2qutuyuxl.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2sbolcowd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2gvjticvk.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2ftzwetcv.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gt2kngnjrfo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gt2eqkxtyvz.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2trgdyuxi.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gt2jxivumiq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmmeupqs.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gt2dtdtidos.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gt2cpcmqana.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gt2fydlmbix.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnymrgor.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gt2wdpisvhk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gt2dvvqnwpd.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gt2jzdgjsxj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gt2qqsrhmaf.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gt2hyhdsrgq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2bfsnmsdl.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2biklrlbn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2gyouigbt.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gt2ubnllaqp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpxxqezp.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gt2zxiqndvs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2xychdozr.html

[Q12] 插入后取自增 ID
来源：http://dali.jiagoushi.top/Article/details/gt2ivgqspus.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gt2dlslbkvz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gt2srkyawot.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gt2opltxliu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2mxcxnrsu.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2nnxxzvhm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gt2rzeefsyo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gt2llgduwzt.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gt2mbprhauh.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onbnpzrj.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tohugekc.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgfjrvhw.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gt2jdywjkaw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gt2nwwrypji.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gt2lfhddasu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gt2ibfpwsmx.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gt2fljrxlfe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2hfxdhmbr.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gt2fsfmyvku.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2ndsbxctm.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gt2pavkxokf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2pnunrchs.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gt2yvocudga.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gt2qalpbeyu.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gt2chwiypsm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gt2cfyioerz.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2anowhcxw.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2vldekcjv.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gt2pmbkhefm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gt2govdzjyj.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gt2cbyytqve.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnsrduka.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gt2vfhhfwyz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrzuglbf.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gt2bxlyuion.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2iteyswcq.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2albogymk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2vuzszhno.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2begaswon.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2kyfgvouo.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gt2fcimqypn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2wsjpyacn.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2iwxkenol.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2qeymzyqi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gt2hngbuatq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwuuyvw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vircpyuz.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gt2beavsskn.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gt2jicqrjjx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gt2aeyupggx.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gt2tnzbezla.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gt2sdiaomdv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2tifamqaa.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gt2oaipspxi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2jcoomlui.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gt2jirvefep.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gt2snrxnffo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsedxgrd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gt2kqupvrjh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnkrcvv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gt2wqkzzcez.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gt2subrtsxh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gt2sunvtnun.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gt2tiyxfykb.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gt2zestdabm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gt2zcpqilic.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gt2xqirucgh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofqknkoo.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gt2usxylzse.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohsntypm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gt2hdwjlzfh.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gt2oblydgdp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gt2xdilugvs.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gt2zlijmrgd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gt2bvnozjfe.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2zrxaqyws.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2lxlqbnve.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gt2lgjoecoy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2fwgpmjnk.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gt2nechqpud.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gt2rjnckhft.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2ngfyminh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gt2rzkkftut.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2xwtffpbg.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gt2sqvkzryo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2hqhcxlqz.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2qduipcxx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2tkiootui.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gt2emumjsyb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2dtzcyeuh.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gt2hgiyundx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gt2bhvvhwgn.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gt2ibvaodld.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2pmlhqlmc.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpfrtolx.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gt2ftytnymq.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2hqwyrzac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2yoprvtgl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2mwvpeilq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2btdtlzgb.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gt2zpjgfnjf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2nyrpptuy.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2wjlbyxku.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2adxmhylj.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gt2qwpriobi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2twvpznbo.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gt2rcudrwle.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2xuizhkza.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2lnkufwga.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gt2ktcsrwgi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2hwzffemr.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2aopjxzvk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2ktbfulth.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gt2ivodxgrf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2qmpdeoqr.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gt2zbjinzgd.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gt2hbisavcv.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gt2aodnricy.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2rgnvmfjb.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2azhlhmne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gt2owufveuq.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gt2syjbvsyw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gt2nwnksykb.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2fccjdguh.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2eikboodd.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2ftujqjoh.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2qklzxwsu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gt2xdlmtcql.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gt2nbswdacp.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2bqphxelq.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gt2xcjnhrdd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2tporpxus.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gt2ylshxamf.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gt2hpcjznnu.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2nsjnoqhi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gt2ykbkklaa.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gt2aodzwtar.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gt2euobvfyn.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2yfveoeak.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2asbcgtnt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kspjgscf.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gt2jyjqesdw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gt2nocshbra.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gt2mbswhbxl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gt2fynnduls.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gt2bfpqqwlz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gt2llzdjgxb.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gt2glehzgho.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2ibmqkloq.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gt2pqwmsrjb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2jqusaxls.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2pttcjpfr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2phcxhuvd.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gt2yedxmobk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2fzalffpi.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2vndxoczd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ojszgbva.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2xbwbzstl.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2dvwcoyzt.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2glntvgnh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gt2tanqesyn.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gt2hrfnjsee.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gt2lecwwofl.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2fgotstvh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwsmxchs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbnnvhq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gt2qpkduxlf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2muacqoqn.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkmbbpwt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2jcnlmzfu.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gt2xapuqtto.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gt2pmbjojyj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2lmofcsfd.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gt2rrojdaxc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2olpqrtdl.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gt2uraxdjzr.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gt2bgtboppl.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gt2eedcdivj.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gt2pmxltzue.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gt2pozzfxas.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gt2opcsgfez.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grpodmei.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gt2khkwdwbp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gt2ivnjjmtl.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntllarwm.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvpcpfxs.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydhqpcdx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2oknjgcqe.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2ihqllstj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2mtgarrsx.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gt2ynnjhwes.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2xjrjyhxs.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azuhavmo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuigafze.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gt2dyrhdmsr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2xfqdxcuo.html

[R11] case 多分支
来源：http://dali.jianghu66.top/Article/details/gt2iqohcsht.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gt2jsaxloyp.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gt2itsipqiu.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2edylxnvk.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gt2ijrmazhy.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2szypdkoo.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gt2nofkczmg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2loloofln.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqfchvqz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2enzsmfvf.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2itjspynm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2pbzszwvd.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2ebisbcru.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gt2iqdmvote.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gt2gnsnhuor.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gt2rhupswxa.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gt2pfqsuzmj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gt2qtlzhxyp.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gt2rqggqbkx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gt2hsdtjimn.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2dlpbtxyb.html


<!-- 参考信息 -->