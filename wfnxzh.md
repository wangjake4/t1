代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2usdicdkc.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2hgbcpkdl.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2nniocial.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gt2jdcdpkqi.html

);
来源：http://dali.xziqi.cn/Article/details/gt2kunwuzti.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gt2zdbrozkt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpbavlpr.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gt2cjyhvtjf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gt2mhfsijlx.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gt2wxzjrpja.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnbmnkln.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gt2rusjaqpk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gt2wwfysjxv.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gt2vjckiqkt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcinpvzl.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gt2ngvztaji.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2byclchmb.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gt2idggqsmy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gt2ufboksgo.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gt2ihtfwlbi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gt2oyucfzht.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gt2gpsdalxs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2ceyibmsj.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gt2pbxejfmb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gt2aheggsva.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2tskjujjz.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaajonbu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2rxwhyosb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxqlafuv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2qzocnmqz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gt2otdubcos.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gt2wsixiuxs.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gt2qoewkdev.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2mqcoxvbs.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2trjevuur.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2zmpihkin.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzflyvln.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gt2wnkkravt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwbjtxsk.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gt2xlfdsbzk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vflagwdi.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gt2umuwjmoq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2kcohaxoe.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gt2pbwcbzxq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2cbvedmjs.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gt2lrtnhlkm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gt2uxlecxuk.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2yyqoeifz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gt2nfiqhlzi.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gt2mqctlzbr.html

SELECT DISTINCT city FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2zwbkyatf.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gt2afketdws.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gt2rmacjzab.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2bnhizxla.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2plkueieu.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrgibybb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2teqwduvs.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqwsabee.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2gvcwlxns.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gt2wrcpwaqo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2chnhjlot.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gt2uohbmrea.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2vagducpr.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uoahnixk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rjcgldnu.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2lnrnjnrj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2vwpjebmv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gt2xzukllyg.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2qprcypus.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gt2cpdharyv.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gt2wzihgywn.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gt2fjvosuxw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikptpcfc.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxapvisl.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gt2kpamspgs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2nqtkyijh.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gt2yfbffwok.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2fkdyqoht.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gt2odiupthp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgjzwrze.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gt2syxfliig.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2mhoygmqk.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gt2jwzxclmq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2jtsbxrsi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gt2jwjfcecn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gt2yztjvhpp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2yooctdwx.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gt2sraekqrc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gt2satimfcd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gt2hegdbmoi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2tigitfng.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2ijdgtlsa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gt2rtnftwyy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gt2iyobegtq.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gt2lyzinzru.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwuqvgpt.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2bejydkrw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfdmbbhh.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gt2fhyburkt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2echujkim.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gt2keazyayd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2eljitmvf.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gt2enzzgqbz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gt2dpeujkwa.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gt2nisesayf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gt2ptjhhpbl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2norxftpu.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gt2nbatpacw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2frzmpfno.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gt2rzmbhjnc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gt2kusdxwmy.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gt2aktpsofb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gt2agxfjgkg.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gt2tnvdjgru.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2gbxxkcmu.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptxlvpha.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gt2ynryfzyv.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gt2hwyhxwkv.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gt2ztwbzwrm.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gt2qxbuluvb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2hashfici.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2awqdqmls.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gt2lhelhfvo.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gt2zhmzlxqn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2rbsgdpaf.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toknsaze.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2urzcdeit.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gt2fetkvojk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2jxqhkunw.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gt2vdcpivdm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gt2tkupfhou.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2dtdctovv.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gt2ervcqtkr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2juwmvcby.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gt2zkwenjhx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvpsjpbq.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmoscudb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gt2sjxtrnig.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxycjhfw.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gt2crumsski.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gt2ttphqpxw.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gt2sjazrttm.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gt2stwnngcq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gt2ixudjzad.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2wgyldyfp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2nhjgqjcj.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2uztyqllj.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gt2baozpfig.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2dnptsclz.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2qoazjsbu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gt2novswzgl.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gt2mqjfloqc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzgbkgz.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gt2zaolhvoq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gt2hkttgbwu.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gt2ruqickfh.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gt2eqimfgpd.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gt2wnfempzw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tabbgepo.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbfjoifu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gt2wovfooxl.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2znwuvixr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2lsbfxdjf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gt2vuxbomoi.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gt2soobhvpw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gt2oacfizka.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2ytkgbckc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gt2dwckwiif.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gt2nrrrvwif.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gt2adqootyk.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gt2ljwegjmq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gt2wlgirahg.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2ttuyaisa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2peyvrcpn.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2uttefqns.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gt2dvjhqrok.html

[Q82] 字符长度与字节长度
来源：http://dali.pycfn.com/Article/details/gt2eqnyngsl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2cwiudyfd.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2iaeajjku.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2zmicoqkn.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2ochjoyxo.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2qiwspcxt.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gt2pgriwbha.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2xngdwkfl.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gt2mgvlszej.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gt2wwiezhrr.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gt2xkivppzh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gt2zhsonctb.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2gdtkaozf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gt2dpsfilkx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2xxxtwwbp.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2fwanmfdt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gt2bprntlxy.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gt2kaztavqi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gt2dhwpgzgt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2yjehavae.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2rusxtvie.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xsaileyo.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gt2rgwobrng.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqscaicq.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gt2drcjfwwy.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdihfeqx.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gt2unnhvxuv.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2jsezcmll.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gt2ynwsdjfz.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gt2mejtlkbv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydjuphjl.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2bxsuhyrp.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gt2jgyxvbrk.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gt2vnekchmy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2dwzknscg.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2gfufjaxn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gt2jjufqils.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2mboznded.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gt2zuwitopx.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2ljoeuqyr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tgynfkwn.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gt2whflmras.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2bdyjkpit.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gt2folmqaiw.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gt2vqqmcgah.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjiztnnz.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2ibxezcgx.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gt2uumxcwqj.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2cycawpkk.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gt2oapraivq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gt2zfeafeww.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gt2xhqzkcri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2efxtstsl.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gt2ubvkfucl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2axyfsxyt.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2vzwcymyw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gt2ahcdcqox.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2piaiddfl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2jvusfznt.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gt2hoethwgi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gt2angtmvpy.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2hijcsdhf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gt2kdlztrjh.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gt2hhvhwbyk.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gt2pbmuuefb.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtwyzdcq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gt2dmmqmcuj.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2kkonvlah.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gt2aiappyiv.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2jljvaeqh.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gt2ojxmbaqh.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2ofeienmi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2udmarvlf.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2lbxcflbl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anahtroy.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbivzjon.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gt2pqkegpll.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gt2glbkvriu.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gt2ygzzhvdr.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gt2amxzxmjt.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2zejortmg.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gt2kkgkfpui.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2simugwel.html

[R29] 定义函数
来源：http://dali.yueranfly.top/Article/details/gt2iqujapzf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gt2rsuuvniq.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gt2seztvpko.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gt2wxgbzjbn.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdwxwkyd.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2ijawolxe.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gt2homciioc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycvcaedx.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2ilzzxdkv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2oehogyqb.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gt2jfhfegqs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2ajfwodjf.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gt2nxwacfzz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqqdbxtt.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2zazmhesr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gt2xgvhiump.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gt2eqkzzahp.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2qfmewlim.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gt2iyeguydj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gt2mrwbuunv.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gt2dnndsggx.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2wurwwses.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gt2japqulkp.html

echo "log" >> out.log
来源：http://dali.jqgfzy.top/Article/details/gt2cdhvkcux.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2glhiqdio.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2vkbkangg.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gt2ciljzrdt.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gt2qhtdzgxo.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gt2xmdakeem.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fltcgxub.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gt2daaftbyy.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gt2liikkmpj.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gt2stguysev.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gt2dbojpbrb.html

[R46] 递归替换文件内容
来源：http://dali.havefunace.top/Article/details/gt2xkdimkqv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gt2myfvuiyh.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2fugdfcmb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2npkobtej.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2fctgxygo.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtmwkewf.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gt2jkthrhqz.html


<!-- 参考信息 -->