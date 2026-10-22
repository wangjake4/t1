代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2mhihsxse.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gt2auxmdvda.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gt2xolcjfuz.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gt2efewlifu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2cjbrbblr.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gt2aixheuwj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymrwtxyk.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2ezkxdfln.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nolbjcpm.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gt2nfzffjyk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gt2ganxydve.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gt2gtprvhhg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2zsgcitqs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gt2whngwhiy.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2syurfcoj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gt2cejllezq.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gt2dkfqqjjb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gt2arrdibhs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gt2uowaxuyw.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gt2wrwqktny.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2nuzzpjdq.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2upbxfcfu.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ufeirbkz.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gt2dztxcgwd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2quillomt.html

[Q18] 模糊匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pizfqitq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukgvrvqp.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gt2cswsbrkj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gt2nhkagzui.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gt2supjizmu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2lhrpqdel.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2valqizay.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sysykeji.top/Article/details/gt2wmepperh.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2mtfacqko.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gt2gecpjaad.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gt2hnndlbza.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gt2rklrkfoi.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2etxcrzut.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2sldvgfme.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gt2ntufrqfw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gt2cnqmodqn.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gt2pzpccptw.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2fqzsmxhf.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gt2yfnrszkl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gt2tcfmolpl.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gt2rwkcmkqp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2iqrsgwso.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2egibflpa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2loqypekp.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gt2supjzdjy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2enueclam.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2zcwwxpnp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2jotcvvqw.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2yozwvoqc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2hplvtjuf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gt2qqnlvzlw.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gt2msparraf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gt2dqcfbhdv.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2xrunekcr.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gt2erqoeahg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gt2xonvpvlw.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2futaydgl.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gt2xwczmpqf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2jzdmrewu.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gt2xgffuwvl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2foeitmdd.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gt2gdbikeof.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gt2ruijmwak.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gt2fnpdqfdd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gt2cldekuew.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gt2ubyshqfv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gt2pgkbfeyp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hywvmfgp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gt2xtxihutu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gt2oxtdgbeb.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gt2rmkfjqkl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gt2ryctfwdp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2rnmeodux.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gt2ntmifopz.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gt2wjikskbs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gt2xbekojdq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gt2uwwkzdln.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gt2vzuueuoj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pufakesu.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2kabvdbjl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gt2qalhvfmc.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gt2yqtklwob.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2iniyrfvw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gt2cfbkadfj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gt2xtnnnpwf.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gt2lstkrzhv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gt2pyhanfon.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gt2qtrcckbq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gt2dvkoxeim.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sschvrvw.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gt2gqgtwseh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haprjkdd.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gt2fyybcblt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gt2gorqxnzv.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gt2ziutzbqf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntfokvom.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gt2zgwvidhq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2qrgmhzgq.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2kpslbemt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjatqdmp.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gt2ynvwozso.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gt2khhluxzo.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gt2lgvaeesw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujxkbotl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gt2qozujyvn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2senbzvcm.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2ejplpmlb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2xheqngcf.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gt2bmrpvssk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2sooxjilg.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzrbvhla.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2bbxsvali.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gt2ckeetiyn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2gpzsipmk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2kwatakli.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gt2sudlnpuk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2gdyjzsdh.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gt2jzlemvxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2tdjpbjox.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gt2soyflffb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lszggpzg.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gt2xovpuuxx.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gt2fhadsfck.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gt2gdqhmxvp.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gt2zavxfxqs.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2uipjnngx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2mfnfxxmt.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gt2pydgdjjr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gt2ovsmpxyg.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gt2ztgrriby.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gt2ahoikbnt.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhugcayl.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gt2hrpkwinm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gt2kqjzepgv.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gt2vfvqghxm.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gt2vfpsmtve.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjzeebor.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gt2fctremyu.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjtkqroy.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gt2kvomedfs.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gt2zonqxgic.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipgernuy.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gt2uwwtcywd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gt2tbxzuzuy.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2nzkqgmkp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2ilsvcdqc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gt2tssycpxg.html

[Q76] 按天统计
来源：http://dali.yuanzhike.top/Article/details/gt2jzvbrwie.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gt2qqiwexkf.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2qfprcmrr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gt2xtzuppsp.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2atpwnike.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gt2ctgpteqy.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2snzgffvx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gt2irbpdmdo.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhqyrvmz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ckgckaha.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2ackjmaqo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2nlzhezop.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gt2eihnpvhl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2cpvshcxg.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2klboxcwo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puqivwju.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymbsimjg.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onxijmzb.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gt2ksywhord.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gt2cimevqbp.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gt2twoteaeu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnqcajac.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gt2plsiynwj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gt2aewsiblr.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2efektbwq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gt2oxeqbiir.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gt2akfytndf.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2lrkbzfzo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2hurtdqli.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gt2vvjawcdq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gt2fmdfhfju.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2pbwkfauf.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gt2fedgfoxu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajckjefp.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gt2bzzlcrzn.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttrmhqqm.html

set -euo pipefail
来源：http://dali.jqgfzy.top/Article/details/gt2apyekfsg.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2jzlluzuh.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gt2hdtggzht.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gt2dfjeunct.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gt2wuzgqvxa.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gt2eezzhint.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gt2xoamzcpq.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gt2zzvdiojn.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niqqvpxh.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gt2hbzdjdcr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2gurwteyv.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2selkpxrr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2qvfdiliz.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2grvumnwf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gt2lthgguae.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2yoejztio.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gt2dsvftdlf.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcdwbdfe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2nrfgzoig.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2rogsozdn.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbskmgjr.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bytlwqrz.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2fxkknszx.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2hnqcwque.html

esac
来源：http://dali.cucudq.cn/Article/details/gt2uhfezhfw.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gt2gecogviu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gt2acryazyy.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gt2xeqcvuyi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2liamzmvi.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gt2ewuioqqx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2iqguwhjp.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2gzxfnwmy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gt2entocrwy.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gt2pfemmevf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2sjmccjpm.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gt2zzwdzbkk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2suummqiq.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2nsepopoy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcneixuw.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gt2lytmasrh.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gt2benjilud.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gt2cltpogns.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gt2hbdtfmay.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2tzirldvd.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2etxjctda.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2bwodnpih.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gt2zceqcuwx.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2elwbklnv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gt2mcwknvns.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2eobnwueh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gt2ibveopgw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2qoenznij.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gt2dzoezmcb.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plcwvayc.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gt2nuchfcqt.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2vtbxdodg.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gt2rxclqotn.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gt2aggkjepu.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2vdspzsya.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gt2tyakzwwz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gt2tkrhjvqc.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2mdapsagi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gt2owhxsgrd.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gt2asirhqba.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gt2dnyjffjg.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gt2sjidaixg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2wfqcozxp.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gt2rjnbfeef.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gt2auzuiahk.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2mrmzwous.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2nqadweim.html

[R35] 后台执行并等待
来源：http://dali.nanxinkj.top/Article/details/gt2vkzxxpne.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gt2kgyxlxow.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gt2hbzoewlc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pukgoddi.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2geygfcoi.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gt2jzershar.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gt2hvcjhykh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2fbrppuzb.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gt2vuraivbv.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gt2fdrvivxm.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gt2gxadghux.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gt2kcxbdprl.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gt2ajiqpggb.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2uamqsrlp.html

[R42] 输入重定向
来源：http://dali.daxiang520.top/Article/details/gt2cxjjtixz.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gt2vgcnopmh.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hapsecjw.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2hebvyfbz.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gt2kxngfbxg.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2qbifsqyj.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2bcsidstf.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gt2erfqllji.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2bmbipckm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gt2fbxaqvdy.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gt2zsqggssa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnkhdkdl.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gt2bumyvicl.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2ciuptxeg.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gt2jdydewnh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gt2wcxvvyoj.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gt2cchxcqfs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2puhbghtd.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gt2lpilwmdj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gt2qomlywtk.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gt2xojgxins.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gt2ovusgizx.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2gspoluta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gt2xqnflqzw.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvnxwaiw.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gt2xljwezac.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gt2rrgvugpt.html


<!-- 参考信息 -->