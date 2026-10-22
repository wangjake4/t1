代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gt2vksbkkpc.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2sfzzuoxb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gt2tkurztpr.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gt2butmvwok.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gt2fhwhvjoa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gt2fyvtavvn.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nardqteb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2xymnvxqy.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcmcbpab.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gt2qnphhdvy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gt2wntwcilb.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xizwomcv.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2bcnuwvpv.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gt2kncueipk.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gt2ufyocrbq.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gt2ptmpzhkv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2lrtqllto.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gt2nakizgjz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gt2hlauwwpb.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gt2qmnwvwxo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzecktrc.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gt2dlhwgalw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gt2wxukkjdr.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2vpbnhqbg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pevvuhij.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gt2phsfxqfs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2phswzaqw.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2kiczvvxq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2wehxilly.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhaosaag.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2izthxgmf.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gt2nifzeqju.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gt2bxjfjcpd.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gt2ewmrsgsc.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2qatjwsaj.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2zcstnovg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2dvlbdfgd.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gt2elndtcbi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2csujxwom.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gt2keirfwdw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2nbgqmcje.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gt2ozxrmzpo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqtysxpo.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gt2dudkwcga.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2guubwgrr.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2xondzleq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2dwakhpko.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gt2cxacwanm.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2awdeujni.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gt2ckzlzxjf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hieqnvlq.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gt2peewnudn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gt2obnxuwga.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2obbnkqxf.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gt2xhixtxdu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2qcjpszdo.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2itrdekto.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2upfwsibx.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gt2weyqhmzj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqfngvxf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gt2ckazzgit.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gt2hnhoqymv.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gt2ednuqlnv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gt2wtjovxvg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gt2aikirndd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gt2jbshrwwb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gt2ejeqwfmh.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2rieezdmw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2nlyjuqva.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulqittdl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2qnpwmzfj.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gt2lelnslqm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gt2roftouwy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gt2mpxjzolt.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2naqalugu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gt2ocrxvfyj.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gt2inkraffk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agruzwwh.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gt2rbptasse.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktkflioe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gt2kcjvauhm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2wfyynsuk.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gt2yskrkney.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2pffzoyvm.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2fnlhotpi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gt2kylsrtkm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uozzjuww.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2lfbthihq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qaanurrq.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2eelyhsjt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2bayjhfou.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gt2jwariewa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2nrhdouyq.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exgiyzqi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2qlwrrvrs.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2isstflhh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvatshby.html

[Q54] 清空表
来源：http://dali.sweek.top/Article/details/gt2lbayrdcn.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gt2nafphpvk.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gt2xxftecig.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2dlibbprj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bycmtlnk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2oifocmfz.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gt2xffptgov.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2ralpxgxc.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpzploqy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2bpjujfnk.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gt2jusulonc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2giyuydwg.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2fxanvzas.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gt2hcslvyjd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2mwqxlxyc.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2zewxxiax.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2kxqqmcrs.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gt2fglhajvf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2egsbaxdd.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gt2rimeljlg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gt2wcqwzgge.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gt2kfocpocq.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gt2ummremks.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gt2uvgcagzi.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gt2zabzbstc.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2lvhyzvnf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gt2fclrobqp.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gt2bqcucscx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gt2oksjwwwi.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gt2kjsmbalq.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2uacmpavd.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2psundnqu.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gt2fdhuzrff.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2omtfcuki.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2twkmrkgt.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmjpahqp.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gt2detjxygy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gt2wqhtccnh.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gt2qlptoich.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2qrzisflu.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gt2syjnkqyc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gt2zopvelac.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gt2nfzociji.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gt2siksyjkh.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2dutirjbe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2sroeeyze.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohxgowgt.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2sfegamfp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2aawfunpu.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gt2jskhmqcu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2ygiauwrz.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gt2ckxoiqdo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gt2wueqcbzw.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2gnpbwfgn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2zxgtdfgx.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gt2aixwzwew.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2xetbublu.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2hdkuesqg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ztcrpuii.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gt2virpeurk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ipyvkhcc.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2yurudxcy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2arpwsrzu.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwnihunu.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2shllecqj.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ioyfciar.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2hevdiiyk.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gt2bbzfdbad.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqstqtlx.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gt2koewimnd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gt2ihjdbiqo.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gt2mnnsqwpx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gt2uilfrumo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ndjgaqvv.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2sfwstuvi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gt2esgtmdqr.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gt2lqzirxdx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gt2xwjffztj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ttpgktab.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gt2jmpfktdb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vskxrsnq.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2wqwwihlm.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gt2imeaaicf.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2ywglthlx.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gt2mredeqci.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gt2bnjfqckm.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2tadkxuai.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2otlltryp.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2zbkboekf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gt2krgvhxxx.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2dorplqtj.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gt2aqdgozzg.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2gkjifljf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2ghphsztl.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gt2cdpikbac.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2phtndgdm.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gt2pluollau.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwryagnx.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjshailg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2lpgrdriz.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2pfrubrwu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2hkfqaukv.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2xamovblz.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2nvirgnpa.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2hitilbqm.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2otmafqoi.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2fvfqepdk.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvpxwqaz.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gt2ovkmgxkm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrwaevoa.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmanyseb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gt2oudgrudh.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gt2shcsvieg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gt2xxaypdwk.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2zxmvgodh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gt2gkzzfhqx.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gt2gklwvitl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2kboxtldm.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxhclivx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gt2yarwbmfb.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gt2bzdrtisg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2xxkyxcup.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2kqcbklmx.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gt2vfqdrhws.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gt2fbjoejnj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gt2jdfptdgh.html

[R21] 字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2yuttfopa.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwioaktz.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2vskhtent.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gt2rhyqjmhv.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2lomfwqea.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvqgusmv.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gt2cqdkzmso.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gt2qwzkksmf.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gt2twnquycq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjzfdqsm.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2hksogxzs.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gt2klbmazgk.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gt2qopbnpnr.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2hwvnpvhz.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2reiscags.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gt2xyflitka.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gt2xzrkbbpr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gt2lkhfprap.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2dkikmlcn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gt2kadivfrk.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2smisrisv.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gt2twkysyfd.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnlpdtwi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gt2syzwcauj.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gt2jvcbvfzu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2iyxwtkma.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2kncevdyd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbhdhnk.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gt2ntednlad.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gt2lrkmgcci.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gt2tszycjdp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2gevucttq.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2ysymkkek.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zdxrvwii.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gt2cxjsibfo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2zosndyvk.html

[R39] 重定向标准输出与错误
来源：http://dali.jyoumei.cn/Article/details/gt2fdyysfap.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2futrvknt.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gt2akdkhmgk.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gt2cfhbbdcx.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gt2reozizmr.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gt2cybvejzw.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2axfwtuwg.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2dnxptxhr.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gt2lpdpxzlj.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gt2hcjbquua.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gt2wgoteytn.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2jieqiejd.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gt2eecdradq.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gt2wzwowold.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxdvofjq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gt2atyyunvq.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gt2qqnhyfly.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frxundsz.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gt2jbtdzglh.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2iszpwzfe.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2gkglkwrx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2vceidjsd.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2hgvonfsq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2ztrbcbzd.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gt2ikhpenqz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gt2wflvxuxr.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gt2vcvteamf.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2cceikvfz.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gt2hqrfflhg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gt2gohsgefr.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aivpbxao.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gt2vnnxdbwr.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gt2hqxziotr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2rqmrmogi.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gt2sibugqcw.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2zhdouqfe.html

[R57] 远程执行命令
来源：http://dali.yongpay.top/Article/details/gt2jjqsmqki.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gt2jswswktg.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lngdmtxo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gt2fybgxxfd.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znthxioa.html


<!-- 参考信息 -->