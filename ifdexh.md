代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2wpvzpopf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gt2xddblphd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2fmyeahfy.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2wzbgppum.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2cvdkcnbv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gt2srklybvd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2xlsbyaoh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ahayquqd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gt2cwfislne.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptijdyme.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2uatjctuc.html

Go:   if x == nil {}
来源：http://dali.9152youxi.cn/Article/details/gt2lpapmadf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2qaisosfq.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gt2abdpfsou.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2bpksszbc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gt2idlniptd.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gt2fsljoclf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2uohanclq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gt2otpkmsgu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gt2nybxbaqj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gt2xbzoxxhg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gt2tiqpybzm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gt2uvnwesjt.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gt2cwgnyabv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gt2rlxzbggj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gt2wzgiyied.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gt2ssjttksj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2puikmope.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gt2wpaaqwwn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gt2fwzcyssf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jelqqzri.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2ksrgyvqu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2dyhfsjue.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gt2tymamigk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zndpwgse.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gt2qgztmamo.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gt2qcsshmjq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2eguhepja.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2tyuzvdck.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2srhdsgby.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gt2gvfrofhu.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2ouyunudv.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnbsndju.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gt2jedablyt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2yprgrkgd.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2ncyyvzmo.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvxswemv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gt2mxrmwkjd.html

);
来源：http://dali.fzhhl.top/Article/details/gt2ztoszfho.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gt2hssdjuxy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2pkgsslqn.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gt2wekteupn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gt2pyqzyzed.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gt2wusdmpjc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gt2icxiihtu.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gt2ddvaquif.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gt2sztmblsc.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2bpzqljvr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2jchwuugv.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2elaikkgb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2lubfuphm.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gt2wwuktdvv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2ijdrgfvm.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2ttferpjo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gt2wmkgslsy.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2aybcyfwp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2xjkcnjfo.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gt2hlmomlht.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gt2ewktdcuo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2zsbudfgy.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gt2upbusbzn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2kmnqjocs.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gt2oanffqpe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2bypnuzwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2juezfxjv.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gt2vkhuxayy.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gt2vdnyectv.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czjrzkoh.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2fmbzgpaa.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gt2suiamdym.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2qhvqcbcf.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2iocnhmba.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gt2ijqyafzm.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gt2olrgravw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gt2derwxvep.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2rabvhjai.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gt2ocyejlee.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gt2pvaxxace.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkmdickj.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvmasjiw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gt2myfycpmf.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gt2qnyfephb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gt2yzrswakv.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2oaxzgpnf.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmqbmqqz.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gt2afmednzf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gt2silizlbn.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gt2mapfllhf.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2dzzkvshx.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gt2jtfinfdx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgevwisr.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gt2pwtdhqqb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2ztxjjtce.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfavftrn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2fvajbkre.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gt2nogkehtv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2xmfazluw.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gt2bmuoxjhw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2qenbdjgs.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2cktflcfe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2dbffvlre.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gt2epgmftiv.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdosbqco.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gt2npiwdyjz.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gt2oqjbypjm.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gt2tuqpmezh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gt2nkobltzw.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gt2oxciglnu.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gt2uwyjdltr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2ofyhhoij.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gt2ziqzxluw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2xxxqfzhg.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gt2vpqzqnpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bolazymt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gt2dxkrynnm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gt2lbpeyuia.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gt2idrnfxlo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2htlgziab.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2oaikqojr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gt2anplzukf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gt2mpimhrde.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2vmavquvh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gt2nxwrjdoo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gt2adkhcimg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gt2bwpzulky.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gt2osvkaywh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gt2hvsegjee.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2wblqafea.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gt2rwwvedsr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gt2prbpcoaf.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gt2xbzejkxa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gt2zusgguai.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gt2kfsohzpj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gt2oqjqykyk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eurhmacr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2bqyqyhgd.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqtyrnut.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gt2zwuyiiuu.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gt2onsosxip.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gt2wtmbqhzv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gt2ewouxgtc.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gt2monzyrwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2nzhsltxc.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gt2ursnhkdz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2gylggznf.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2sxcpmepz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yutyxykn.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gt2uxqhorjc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2tbofwyoz.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjnvbivf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gt2oqoywrkt.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbvhpapx.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gt2ptgtalgj.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gt2arjwoivx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2srlyjiyn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gt2cejeegyg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2ujumwpqz.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gt2pgntkccd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2rkwigynh.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gt2vvzrrpny.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2iobsycft.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gt2exfoedio.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2szumdjnl.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gt2dlxwigxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbgmalti.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2hwkramkt.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gt2xhupawpb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2pszcxddp.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gt2xmovfwwl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2jpjsamtg.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gt2lghnslha.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebhuegjt.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gt2jlrrsxgi.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gt2sybhizym.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gt2zundaslu.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2olntduzj.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gt2uunjvbos.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gt2ejzbozsq.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2ccdywmbi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gt2calrdygy.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2kpsqghik.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2procvbhr.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gt2ibzjyeoj.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gt2awlxptus.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gt2jguylupu.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2sgjiwsmg.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gt2phxrwggr.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gt2foqadpwq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2wazhzefs.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2uvvjsfee.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2sqynhhiy.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gt2yeltrstv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gt2kvtulehn.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2hbfofkxo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2elbovgkx.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2hwphbdzx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2fmczyzaa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gt2reuzlqqm.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gt2qdziwuhy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gt2cgebpcty.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwplvazn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xstxspzx.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gt2atutkpfa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2pdsixcfm.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2ezavwjac.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gt2bvznysoj.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gt2yudpllox.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2qcbytoup.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2nelpisiy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2ceqerggq.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gt2eybrtvoc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2gpjuwhzy.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2tjpmmfyo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2vnueapbm.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2zieqttbe.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2rgxxsxjp.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gt2vikujjyf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2avvtycnn.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2twccmblf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2evlebfzt.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gt2ddzyjomq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oowzqngd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2qmockkga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eryljstr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2uggulrxc.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2sypjabcb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2kesqztki.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gt2enfxltww.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gt2jvxppnzl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cjllgqec.html

R. Bash 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whkghdsa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2axdvtmzw.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2kfwsefze.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gt2msyqsxwm.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctxlkttx.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gt2prlsyyte.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gt2grmfvfnw.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gt2fryltoca.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2kfqzznzn.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gt2oweytwgs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gt2ykpsbkgt.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gt2nkifxdcj.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2yxwwiiuf.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2kykbsmwa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2sxpexdkx.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2yfgzmikd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgatruzy.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gt2iqlwiajc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2hmhhelbf.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2zhdhulcq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2ntvepres.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2jhpgdqpr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gt2koluwlif.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gt2vbcimfdc.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gt2ssdiqtaf.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gt2xpcfoljo.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2izibvecw.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gt2pqpzvpwb.html

esac
来源：http://dali.aibaodan.cn/Article/details/gt2lwgwgwbs.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gt2lyuoivyw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gt2aeghvgtl.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gt2baaelfgn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjxziiot.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gt2fnijwgoa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gt2jweenlfr.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2opxfuidd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ejdcxnap.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2udfxzopm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsjfalxf.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxkpzlwz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gt2dubncslq.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gt2jdmczejw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gt2aahzijwo.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2fxdtdmdk.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gt2vvrzrxoh.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gt2nczsigve.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gt2zggdgmbc.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2uwqdgtar.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2esaczqxh.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gt2pnmamlds.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gt2ryputjxx.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2jqozmafb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gt2ybdlzuyf.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2gbmkukpw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gt2wqvtgrwf.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gt2gsiaivug.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gt2kgwirsrf.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gt2yutiqfab.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2gofriqjt.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2ajenfxpd.html


<!-- 参考信息 -->