代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gt2oevsnrxw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2jzxykvxh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gt2tsvwysdd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gt2rscfkxxs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yloudhgx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quynycla.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2rxcmfvea.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gt2ojuzvzyg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdlouuim.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gt2guejphnv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2ypxaodza.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gt2tfrbozcq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gt2mrtbigmc.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2otqsmykn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2gkozohcq.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gt2awkweghw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gt2mouqzcwk.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uhhbfrlc.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gt2bkolxmfh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gt2ixbvzici.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gt2xqawxonz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2pkywobey.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnpevemc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gt2odmtspnv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2evoqgyop.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gt2flckznjt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gt2lamghexy.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gt2bbptyfmc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2lvgqftem.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gt2nigiyuba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gt2imkokwkd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gt2qnkpqrpf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gt2wmixakrn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gt2qpcrbbbh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gt2ccxwzfby.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gt2ughfnseg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2pzctkovq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gt2azmvtadi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qchtddur.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gt2uawzdtyb.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gt2pctigqke.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2bsjztnxi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2nnuvxluv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gt2xsjctyqp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktwdoshh.html

);
来源：http://dali.xuanzx.com/Article/details/gt2xxbnzkoz.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gt2ifysylbg.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gt2rjpprkdp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gt2bkglxlmd.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2hqenslao.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gt2niobshei.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gt2wolfqldo.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfdumwej.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gt2uwhxnimx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.svipenyu.cn/Article/details/gt2wwvifwpw.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gt2pvqpywae.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gt2wiqbdlek.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gt2jyrewuhy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2idgagmmx.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gt2kiwhlyvc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gt2ikydnlzn.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gt2oudyfxqq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gt2yyatwddz.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gt2crcodjds.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2ccjolpyl.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gt2osvdlbsu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2psviywhr.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gt2nabqzqow.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gt2piscsfee.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmpftpuy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2esonarwa.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2sxljvbnf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gt2ulcdvqzm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ybcxt.top/Article/details/gt2qzvzzqdn.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gt2fssmbarc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xctxeenj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gt2zjicerpp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gt2rcsawecj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksgltfax.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gt2hbxjpioh.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gt2furtscpe.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gt2cclynaqi.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2queyegny.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gt2xousuvcg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eappzhoz.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2xyolkbit.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2hizanpwr.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gt2inoacixr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2qagzhtuj.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gt2takyggrk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gt2aethnuoe.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gt2hbketjdq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2wckjyapc.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gt2nxnknvdc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gt2likfeyho.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boygsbph.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gt2hocpuljs.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2yfvdshag.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxdkqwer.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2wzfegbhi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkyakdcn.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gt2lqekzfks.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2bgdhgisk.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gt2cqorhdnh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ohhqsudb.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gt2hjppisfa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2ywsnkksb.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gt2evbzdcmy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2suooiuwf.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gt2zcvcfwwb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2vumbtjfk.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkjxzdqb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2txizkpgi.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2egrsyjsh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2bcsdmtvu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gt2qcfrqmlz.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fppsmqug.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gt2gjxkygxd.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kimuqssl.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gt2gsqyypwq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2ugvuwigs.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2rxjouxpn.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2brxpzrio.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2djqgycnx.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gt2xmrocipp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gt2rejgtfju.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgqphapn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gt2njoxqgit.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gt2maejwbmx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2qilymxvr.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2upybhpvb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2imckwsfc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2agnqekhf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2bftzlryi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2qexzucpo.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2fuepqnsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gt2umztspax.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gt2zxqyouzx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2lomjfyrr.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gt2qfktticd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gt2surghlpe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gt2byzrirjc.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gt2sctzvtfj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugadxbwa.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gt2duiyhyqx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gt2tlyiwuqk.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gt2oasbolfp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2zylkeubv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gt2gylngbxu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2mkrhadwz.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlckcryv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2geaczsfa.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csfhmyyo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gt2jnpxttpy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gt2tgczajvf.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gt2mrutaufw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gt2vblukumv.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2azgxnnlj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2larxbebl.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gt2xmjddxjr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tusqdoey.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jquppbkc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dudmercq.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2dyzhlfzh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2wpsatqxv.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gt2nkwkkrgb.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gt2xlcjgjol.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gt2civvsdpm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2jaojkbub.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtkgfjqz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2belnlnbp.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2qslskpcx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2lgpnluwb.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2bohgxifg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2cnlhnpve.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gt2lwkzicvb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2ntfigzoo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2djvhcxgh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gt2ewabezlv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2gnlnnuwm.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2zchyxrrb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgihupxs.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gt2vktbocrv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2jkmblold.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gt2iuhjltyg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2ruorsgji.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2tbvivszt.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gt2aygnygxi.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gt2uxbxdigi.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gt2sfudzybx.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2zcsahhoo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gt2wgdllhwj.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gt2ggpradhg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gt2thidfdup.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gt2eicqzqta.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2ncduakcz.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gt2xegzyzed.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gt2emrfydbo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2javnyqtr.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gt2bostezgr.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2epeshmbr.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gt2qkdoyacm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2aboxtynf.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irqyasbe.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2zqwrlfln.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gt2qltbxflw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gt2sbkqwbqd.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqwlrtat.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gt2lncojmms.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gt2dzqpwctd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2fboganfv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gt2aeyaktqw.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gt2bhvyebnl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2rvjdssvb.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gt2lldjgzux.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gt2tfmdkycz.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gt2flkpetxu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gt2ageijqth.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2yrwpvrxx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gt2oxijpxpf.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gt2ushteczr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsfqurhp.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2reovxiyd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dizsqkis.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gt2zsdsmlqg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2qswnkijx.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2ldgraveq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2qlsgfqrf.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gt2ecikmnuh.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2wepqafcp.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gt2pezazrju.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gt2wixxmfeu.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gt2pejdvngi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gt2ednyswcb.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gt2cbwsaniz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gt2kuhekuib.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2cumlnesv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gt2achkhazw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yedadvry.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gt2wasswxww.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2flslhgpr.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gt2dwoqvezw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnycbtdd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bybphvrr.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqjafhzx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2peixlzty.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gt2jyctonsd.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdslrutk.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2goaerqcu.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gt2rjicdsmf.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2jegaevav.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gt2ftfrinwr.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gt2obtgifss.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gt2blfpwzfz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gt2cnayhjzh.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gt2vmtotgnz.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2qjbfbsdg.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gt2fylibrqm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2lnkihtwe.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzacnetz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gt2esmpdcim.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2jyuctmly.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2suvcxkfl.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2hfwetyge.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2deotqzic.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2iltdqgak.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2hjdejple.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gt2ninvbkog.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gt2sapfiast.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gt2mpaumiuj.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2dwrwoodq.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2tvyvdnyp.html

esac
来源：http://dali.xylfe.cn/Article/details/gt2diylcvih.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gt2gpqwrola.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gt2vruwcxlr.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gt2fyktfejz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2ytkpssyd.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfeixmeq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2qzeozxlx.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2dyhbkujx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywayhlqm.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eokfawnz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2swyhybyx.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2dkhdzzhr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gt2gkzzkiby.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwbxcxaz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2ocqeurmm.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gt2xsdiyldi.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2gkxaoius.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gt2wvgfudvb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gt2zpbyjkeu.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gt2vtshufxi.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2beziwptu.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2nsvikpqp.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gt2syacblxn.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2okvnijog.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gt2zlbwymqw.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2tryeawfx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gt2bqjdcdtg.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gt2mpxdxmbc.html


<!-- 参考信息 -->