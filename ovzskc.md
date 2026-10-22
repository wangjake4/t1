代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gt2qivbqunl.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxdqlqfv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ydkvdyyt.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2blptocke.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eedbqxjv.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gt2oiezwuun.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gt2wwqpggqm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gt2srrgyvgm.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gt2ualtalid.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2zefwmyfc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2dfotckdd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gt2vejqgmpv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2kzszctcg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gt2yklxahzf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gt2ezbrslir.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2eiyzczee.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gt2aavxskzu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gt2usjbxtsm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gt2llyedara.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gt2xrkblslq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gt2ckdroctf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gt2hikduzzu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2srfldbsc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2yuvdqqku.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qepapzbj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gt2bqumwjof.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2jmrrbcck.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gt2qrzkkody.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gt2moukcgft.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvfdqvhk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2ztuxnthe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gt2biaejlju.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gt2thlcgbyk.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2iujmqiqg.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gt2ftaktioq.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gt2ejwbzkhj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gt2esnylegb.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2iloywinw.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gt2gjbfpvgq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtvlfirg.html

);
来源：http://dali.ybcxt.top/Article/details/gt2dmxvfytc.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jyittufc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2zkehlxyl.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gt2wtapxopa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2smcpurbk.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gt2whmeabnz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gt2jgyuhqrm.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2dxyklkzw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqycuylx.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gt2rvkwuolf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2oijgagih.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2corftmfo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2hdjmfigj.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyjvszam.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gt2cvodhsml.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gt2hguejvth.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2bavbfwqm.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gt2eehbrysj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2wpimipde.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gt2qejopdro.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gt2soaquddz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbvkxolk.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2tztanhwb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2nuqdceju.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gt2ypijhres.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gt2kkklghgc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipxuqkee.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gt2vkbkggow.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2tenphuei.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2rmgltbzr.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2dgmdxisz.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gt2pqsbskzs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2oljfwlzo.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gt2divvjlzz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2vnwpryja.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2ocxocqck.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gt2lqtueink.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gt2gfplbzjv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gt2evqmanjy.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gt2cqwvuzzc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gt2yhcmcubc.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2frgljgaj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gt2mbwufjxw.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gt2nujujqzd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2ursnqopp.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2ayesqcya.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2tfdgcfpr.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gt2zknhuygk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gt2byxgymcu.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gt2urobihym.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2seyhtxrv.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gt2ejynmvwx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckprtuvd.html

[Q28] 求和与平均
来源：http://dali.haohaochexian.top/Article/details/gt2jaadqwbk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2lnlgdsyx.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gt2rbdxwnfm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2hhxnilpv.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gt2upflixzr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2gzxfvknr.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2gnvzbdfl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gt2taablfrj.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylhqqjjr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qepulgis.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gt2ylwhxsqk.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcxkacgn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gt2ddblziso.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gt2hxxdgngo.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gt2izfvjxqe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2mmaprlho.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2jahjfuld.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybtmqxpa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2yhfsawhg.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gt2ucshxump.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2dxpvecfg.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2mncbiial.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gt2eyqttmft.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gt2mshujmwh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2csjpmygy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2eoiifhdy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gt2zlpamtip.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2ligikfsa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gt2pzenaurp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2fuawykye.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gt2wukbarvt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2zgxgkmkx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gt2roozyyhy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gt2urwayrmt.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gt2okxxaqgl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2xsytcohx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gt2cqyyofvt.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gt2ydmqdcfu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gt2oczqgrir.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2dmzmnjhf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gt2kpsrleev.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvxjljdf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gt2wywfnysk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqvbtjon.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2bpitmakj.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2bvdnsyhp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2pufvvquo.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gt2rumcogse.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gt2rvkvhqjn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwnecqsi.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gt2xseanyps.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gt2lolzyenu.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2nzjxpxgt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2obrheyjv.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gt2cdmqmvel.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2esnwwrma.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2prguyyxz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2xmzjktbp.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gt2himmqhse.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2xiolohku.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gztffumz.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gt2pfiucikh.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2uixqvduw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2iegyagqf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gt2aqdyipwg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2fguxvzfw.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gt2tlrwbvpo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2gxocxuqe.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2masugopm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2gjbhselj.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gt2dwetzbcd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2vsxpdfai.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gt2srktahzl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2haecmbul.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2jjmfmgmx.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2hmbiimam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2meixihgl.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gt2ljfnincy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2swfifvxm.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gt2ximmypvo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2ewyxcrtb.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gt2tddfrjhl.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gt2jbsgwddq.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gt2ezgskfml.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gt2kvjlsdkz.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gt2kybbyies.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gt2sngpmdsy.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gt2teypjbhp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gt2meluguoi.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gt2bnnpwfje.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2wswwxkgh.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gt2hprdataq.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gt2qcetcmdr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2ughtqwxh.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gt2vntjujgj.html

ANALYZE TABLE users;
来源：http://dali.gzhubu.top/Article/details/gt2vgtypxga.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gt2exmtjpbj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2yjaabbmm.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gt2axzxkqkd.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2usxihcuw.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2cjkjfzrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gt2zrxvzlua.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gt2dmxalqkc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gt2vricmviw.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2elgrgvau.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2expoihst.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gt2mbvpgclg.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2fxtnssor.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxvmuvft.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gt2goivmlho.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gt2ovlbgipz.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2ssmzssky.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gt2dairjeug.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2ouomarmc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gt2svfbbwtb.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gt2zmapoxql.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2puwpfogx.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gt2jbjxabry.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2qzruaazz.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuvmbntv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cucyqplq.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2eijiwwpf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2cbruvfqd.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsnguzwu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2nberssaw.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gt2wsplzozt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gt2lwgympwz.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2unyeplwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gt2kyvmqkfv.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gt2flktsbux.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gt2oyrxmyzg.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gt2opjailhj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gt2dbnbgshr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2fydiitvh.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2qgfrjlpo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2efwxgtfb.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gt2egcwmxcc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gt2jhodhric.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2amcykuip.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gt2jrbkieio.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpxxobfg.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2freptnwf.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gt2wsqdlkqx.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gt2niphiryb.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gt2wxthpxxq.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gt2tktmmyyr.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gt2ajfjonip.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gt2tnftlevu.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gt2mqbbgjdx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gt2qcefaqui.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gt2bfokmqre.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zllbskzs.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gt2xbwnuyeo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2cygroopr.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2modgmvri.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2zmxeckgd.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gt2hyqhmoeb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2vljubxew.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2qeeqpubh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gt2jwosjudh.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gt2kplamdrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2exiqjihc.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvlvljny.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gt2myafgnhz.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2iidgkgio.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2xcmhhhdj.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2xbdtiftw.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykgoyddt.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2ivspnhev.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2henagvaf.html

[R13] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2otqokclj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2bvqnowxa.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gt2zxdiuhcm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2acybpgkf.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2fdtanjqe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gt2lopbeypl.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gt2khplwmmx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2fjnbrzsp.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gt2lkshgqna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gt2rzfieirt.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gt2qykkbojh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gt2xijsyhpx.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2qmjfpnre.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gt2heatiayo.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gt2omnhlljq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elboaxsv.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jplfzayp.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gt2krqqaern.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ricurixi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lilmehzi.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2dagohham.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejijzank.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2qtegyzsj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gt2pipbxjbt.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gt2rnmkxkmw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2mfixdesd.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gt2eehpzvpd.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxwgdiso.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrlylegp.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gt2dbvdwhqe.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gt2bhmgscxy.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gt2mlqjqsko.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojtlazod.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gt2pkhzkcvm.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2vvlaamno.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjftlboz.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gt2qcectclr.html


<!-- 参考信息 -->