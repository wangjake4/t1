代发 wailian999

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtpeaqbucv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtqjxumcqh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtvlvykkpo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtgethvljq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtfsramxbx.html

);
来源：http://dali.guowangkeji.top/Article/details/gtyccfieao.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtcvniequk.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtbqdtrdrq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtnrywaeup.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtbrwcawvo.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtzmrjfrip.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gturbvnkfs.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtrarirlpt.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtlipqkggb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtnqwaenex.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtsljxdlez.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtzissggwb.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtkoklirmu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gtwkoagxnc.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gticizqbbi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gtqokppuuo.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtnjhuertr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvxngtnk.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtjvpspxts.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtforusggr.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtfnozygoh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtqrzfdkir.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtzyonbhfl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gtolinkcrl.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtyrilbtjv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtsfrlkdvg.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtpyahltyd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmhfwcpq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtulcjvcnv.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gtulzruxnw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gteemejkdb.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gtvvuxstaj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtpkudhyqt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtdgowehye.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtiflawszt.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtepvkgrcy.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtcbhgjtpk.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtltydvknj.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gtjzdggltd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gtinnecnkv.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtwsxeemdc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtsbfptzqb.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsxrcluv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gttaleunkp.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtoyywzyvb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtvezhdnnz.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtwgkqdevu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtuhdjmljy.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtmbqhlryx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtdiowwzhx.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtlvqvaqev.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtaqxyssnz.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtbwdpsyxl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtuvrrssag.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gtaqghrzrg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtevckfzmr.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtbughxuup.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtoqcvngrz.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtswwjpury.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gturyyblmc.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gtmwfoqyag.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtgnrekoci.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gthbkrkujs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gttpxamxzl.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowuynmsa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtmmvyrisl.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtrohkwqff.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtylxhhiws.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gttdseknnh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtbyitjmkv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtlelxqwbg.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtslqobpxj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gttaonvswa.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtzisvcoyh.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gteusqzpto.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtajwjlsgc.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqdjxthr.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gttabydzcw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtpyuwluqk.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtvqfkdunt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtyttotobn.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtubegmjvy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtvocfhsdo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtkwrfsdwd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtegjnleec.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtvubgzymn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtsbofisyc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gtipjzjwtw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtnrrikdik.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtxqnnnxwn.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtttuogusw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtytygfftd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtiruzocao.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtuyflrmlq.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtabfbjfby.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtxwlfjmjd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtjchqrdcb.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtgbiekxdy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtnrskzjlz.html

[Q44] IN 子查询
来源：http://dali.hammf.cn/Article/details/gtfztfvtuq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtrfbfxcxn.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtxbzemtdk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtunfbqziq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gtillfisof.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuxxqshq.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gtjngxnaus.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtmdpewhyw.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtowjcbhxm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtpptmxbuh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtthwieuaw.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtdulipiuz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtddcsolnq.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtnskixkyp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gtanqfvlpc.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtofftpcbi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtuvjvjxjb.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtqaxicvve.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtmkzymmmz.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtaaiafjif.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gthpxsrfeq.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtddnicpzn.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gtygcvvdpa.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtmjvizriw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtwqijaokb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtxghnufrd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtbjmscqjl.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtrziubvvx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvsbouyts.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtxjzqzuhp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtdmimqlmf.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtjxbgmbso.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtltuantwy.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtorawbgrd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtvapyempn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtjchoynyy.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtnpaacclv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtrplaynth.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtnolvxbgw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtusrsuxbf.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtwbhruzvz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gtqzwdzdfe.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtitvyoipo.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gttrpfcede.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtqhpiqkbs.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtchkeybbg.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtgxaopdgw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtqlywajaj.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtevsxlkyq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gttoeowyea.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtkuvqdcdy.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtrsxskpdd.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtprvdwjbh.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gtpjbzeaym.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gttwgjcevx.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtptyyyzer.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gturdhbwbs.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtbjmruqaa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtwltcnnts.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffbtkilv.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gttqroewwu.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtzhyjahoe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtlacsskwc.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gtnimnfhea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtfwnofthe.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtzurfxifb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtohmupipw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gteqywlkug.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtwhwgfgke.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtgslgagbz.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtuexxtmrt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gtpfvgxjkx.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtclorognh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtmnxmlmwx.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtlbwgoxfq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtgeajryjq.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgdpagex.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gthastmedr.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtatopwkqz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtcufbwcmd.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtfdlxbjox.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtvhmogqlv.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gthqtnhfjp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtxrocshra.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtqvunqwjv.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gthssvzmdo.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtrsxtfbux.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtmjhhxeqf.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtondzsrgq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gtvbwkwbjp.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gteoqblbzf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtjuzlizem.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtrpycskis.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtwbxbmhdt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtowxrqtsp.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtcjkykdwg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtxffmgtuo.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gtcbpoyaho.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gtbsydwsft.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthjfobrvv.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtskzswxom.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttrmkxnaq.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gtdevbwtmh.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gtppytgvwi.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynqlxlif.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtvlmidscf.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gteehajbtu.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gtroedxsar.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtaxfzjytv.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gtfnsbsjox.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtweywsbes.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryhefglg.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtjsomufcr.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gtfllfjeml.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtkdgnjzvd.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtyrlhzkyr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtjldpfeby.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtywjnhptx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtclexmfjs.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtgbgohzsj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtcljiqbmh.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtpcdtlubh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcybapouz.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtfndcbugl.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtobdaxbta.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtsgtzkcpm.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtjadtvxpr.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gtunhomdmc.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gthczyormu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtrvktgqzh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.redwolf501.top/Article/details/gtlyptfbmm.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtqvfhuvnk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtcqatmnxc.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtlhnlxvdk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtjqkbugcx.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtddjzdwmf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gtjuhsopon.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtfceaqmaj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtwxrgjkup.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtrbjwzcyg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gtygwbqhyh.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gtedxevnmk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gtifswwgpp.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtcntwcncd.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtfvsimieo.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnavufek.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtlfmhdiue.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtezgrrqdj.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtvryuxykk.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtusscotkn.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gthrptirza.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtvxhdurwp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtjwnswynt.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gthtefsqtc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtvotgvwmt.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtttalngev.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtlvffdxsg.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gtmfaykwgc.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gthurotktm.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtygysncun.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtflsnzchb.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gtxdltxvpu.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtffkyzgoz.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtzhwihvhi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gtgujsaexk.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtcbpucelq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaraoxpkk.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gtjceqxpxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gthcxlvyly.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtlyjrlgnk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtqxavofqx.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtgqdujczu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtsqgggdja.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtrkulqbaj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtfyhkofir.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtaflpadyu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtizaacspy.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gtxejwcjry.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtqenivmpo.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkjaanjsc.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gthvclqzpu.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtegzbbbwe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jlsjyb.cn/Article/details/gteejgdvqy.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtehvcjfez.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtwznocadl.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtcryrjuna.html

echo "log" >> out.log
来源：http://dali.zdqjudy.top/Article/details/gtbmieuykg.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtoavhvbvz.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtpxwlxhyj.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtrqjybxpv.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyhlsghx.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtiofefxeh.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtlywgoflt.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslwultld.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gteeakllnx.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gtshfyjhbe.html


<!-- 参考信息 -->