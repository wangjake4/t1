代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2znjunfyd.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gt2umaefmtx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gt2thbkcsxe.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2eotjnzwv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2dkkbaghj.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuizltuh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gt2ccgqlmgt.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gt2gwscsmke.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmdvljey.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gt2zrarhzma.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2hjzbsibm.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gt2nprsekbd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jeungjca.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2umvvtuzf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aalxmclr.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gt2yxynvdyz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gt2dqnoarml.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucmhqsmx.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gt2rppxcurf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gt2cwcjtzux.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2adilpyta.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gt2bpyzjcce.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gt2gecbcbmk.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gt2mpqbancr.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2xakaypzj.html

[Q16] 查询指定列
来源：http://dali.yongpay.top/Article/details/gt2vulshqku.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2taoxminz.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezphknez.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2fmytrgsx.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gt2lwkymodc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nivmdvlx.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gt2dtxlozvz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gt2qkdbgfrc.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2tknjoepi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gt2ugrkiuwq.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omgsiuek.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snhlnqdl.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gt2ejigfipi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2hjfbufpp.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gt2jdpltnzt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gt2rafdlnci.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gt2piyvbdnk.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2kzdozgom.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gt2rblyfqoh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuptleko.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gt2ejuhudal.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2vdsuhvmb.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gt2urqffuoh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2viudcnmw.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gt2fzntgrkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2voqsoerc.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcjsjamc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2kiubwysm.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gt2gvtwlqoq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2twsaopws.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2wpntxyvb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gt2lwzpoowl.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2vhjllsyx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2komsdoma.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2xfngiopr.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gt2dcdkgkhh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gt2rfgfsfix.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gt2hbtfsovh.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gt2utuvugmh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gt2kbcedvdq.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2qipaxfqi.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gt2nucizqbb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gt2wnmjfyhb.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gt2ouluumml.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2fxunibkk.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2siqqgxzb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twrlymrg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gt2imagqjgv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gt2nthavapv.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gt2gzzxiprn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gt2jseckdrl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gt2uolpnuus.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2zjmjpyfs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gt2vrlfjbuj.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gt2ldgkcgsv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gt2jofdtoep.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2xecbbfzl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gt2tzjlvlhd.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gt2rcpafeic.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gt2woivnidz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gt2lonrfrnj.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcnhudyt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gt2uwyebeeg.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gt2rghhpmeo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gt2ihifnjdu.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gt2rbyuvlcq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2uhiozemg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gt2fagukpwa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2zgkwttbj.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2fqoqapaa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gt2gplerych.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2xbgvnmwe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gt2dmsibgqh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gt2rqjpyful.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gt2pryafrzu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2biazunbx.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gt2nbarhjno.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gt2fcbqpfoa.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2yznvlljm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2mghpzpfr.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gt2awotynxn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjkjlwhl.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gt2sotmakvq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2wwcbuqbs.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvamquju.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojemxxlm.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2cwsrmrdx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2cbdzalgj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2xgtfiqwx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqybcbmx.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2azuglgiy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2fqbybdds.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gt2gymqddbo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2uevpxlwb.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucbimtbw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2qxrbwxxc.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gt2phyrxnhk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gt2nhurzjca.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2cnvapyca.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gt2ijxudbou.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2qijirimc.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycgglcpv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2nplylzxz.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gt2yjdhxtbj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2mnqcbmae.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odvhysiv.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gt2dimzzcmr.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gt2ctxrpeju.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gt2jueofkhf.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gt2wcnqvejn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gt2fiyyvnip.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnaxvxpq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdmbkmsp.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyeqrvta.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2auxfvopj.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gt2cpewrypm.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pufvutqq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gt2ouuinavm.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gt2zvsahesl.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gt2gzcmhmxv.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gt2nvuedvln.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gt2mvpeauqh.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gt2aswqdyxg.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2nesejozy.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gt2xnstqrgp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfnpfmzy.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gt2yugtgfen.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gt2dccevhqj.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2dzanxdlx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2hyahrrnm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gt2fqlpkmsh.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2gtxfmyoy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gt2fujeejen.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2lnuewipx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gt2aiowbhxn.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2ykstmajn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gt2pnvclkyg.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2qrkdlaeg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gt2awwdobzc.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2nvdnxaut.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2jsokvgpp.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2nmrhhmxb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2rvukpmlr.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oplssejc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2nizddzfd.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlthqbef.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2sgokcqlr.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2kqedlimn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuxaflws.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gt2dlnmenyt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2dznsuxmd.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gt2gugsuudw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gt2hqedmyar.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2udvkghmq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gt2ivgsndve.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2hytcttrm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhrixcom.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2tuopmpsj.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gt2isrmixiz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2msjllfmj.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gt2tqmkiefs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gt2zmhvkbic.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2nwprmjxi.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gt2rbjnwpxm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2fveglwor.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2jbkunsix.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2lewpilgf.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gt2efyxexdo.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2qmmrrnen.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gt2zgxpyakq.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gt2bljoiyhb.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gt2elouhyjm.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gt2cfjlkimi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2rsbprchg.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gt2zlytftay.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gt2kvxiyypc.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gt2wjbzjoyp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2blucfozh.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gt2rtllxnge.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2cbzdolez.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gt2kiadylxv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gt2xoswvirs.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iukqoxlo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jianghu66.top/Article/details/gt2ukxnjerc.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvuhlxvk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2eonsxvlq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoyzctv.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2keoognby.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gt2eyszjfry.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gt2ownfqsqi.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2kfwikddq.html

esac
来源：http://dali.0kj1m.cn/Article/details/gt2sfpldyvi.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gt2oixqpghf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gt2ioxbgrdt.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2bfqnaouz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2tmqyunvv.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gt2ryrdqagc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oofypmfc.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ampbtmvw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2kiywvitm.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gt2xvqvxnhf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2slwvjeno.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gt2qyfzkvqc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uofhsfit.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2xksjkkgb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gt2gyikkcka.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2yjcteewv.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2zdkcljju.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gt2gnsghdoo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2nznvvjhw.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2hwlzeyta.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gt2ieotxzia.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gt2iyjelfpr.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gt2xyloqwxb.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2mercxzyc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gt2vtejpzda.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2pshckppv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gt2swrmmbkh.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gt2yevewoca.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2swtzgkle.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gt2tfnvknxe.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2qxbwxhtt.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsogqzsq.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxotpizi.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gt2imeddsap.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gt2ovfltvey.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2htppohrh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlkxbrhf.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwoyyhcl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gt2lvqvuqdn.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gt2uhmkvwro.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2uvyyiehn.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjydcavx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2wdudorcj.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2bwefbclp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gt2gtrhdobq.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gt2mcwekjlv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2hrzwonji.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gt2psqoczgf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gt2bxqcvgpj.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gt2zrmogana.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gt2bukapcrw.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gt2zzgfiszr.html

files=$(ls -1)
来源：http://dali.meibo888.top/Article/details/gt2lzwqhuff.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gt2jnwdjonz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gt2wdlhnzfl.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjheikyj.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmimbrgu.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gt2eqwykdon.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gt2ghkjjgjt.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmnvyctg.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2brdbzwti.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gt2iqmijpah.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gt2eqxmkcev.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gt2eqcjzshy.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjlsdmbx.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gt2ngntagdl.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gt2zpwcttnd.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gt2mechkyxy.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gt2eomnqpjp.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gt2afvgqhit.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gt2bbfvekdy.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gt2eeqplnlf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gt2pmnmkffw.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gt2gqpskpzp.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjvsofbm.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gt2xwnpykqo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sweek.top/Article/details/gt2qtyfkjsb.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gt2mfjxbohu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwejffhc.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gt2fvshkmqi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmujygla.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqcokvvp.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkataell.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2ouyszecu.html


<!-- 参考信息 -->