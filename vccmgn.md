代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xktvwmjg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gt2cnvgolnn.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjqmwmlu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gt2mwlnqgfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gt2qlrsedtl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gt2rjoekyjh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2ycueghws.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2wblkgnks.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2zwcxqrue.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2pbpyymie.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2laqoyysl.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2xlcqzcpp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2uzuasgug.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gt2zprdudum.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gt2uniwjill.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2xjalxyqc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2hcssryar.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2jgcoynon.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2pcjwsfmf.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gt2wccbzmug.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gt2dcsgfqle.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gt2npscnivr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gt2hkzegito.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2rimpriww.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gt2hotmdebf.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlupgqeu.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2jasbjuqv.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gt2bcbvrvts.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gt2skurrqfb.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2yitxjhos.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2mkmpyvvj.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2jtiqkdfc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2bzlzadgb.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gt2phbxbkhh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2pfoiocfz.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gt2weipdzmw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2rftygxwf.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gt2rpzzarpw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2ghmojyuh.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2yktxhzgy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.snrcjt.cn/Article/details/gt2iwjqvgpq.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2zjhyzksm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2bbdmlymh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gt2kbgliknu.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gt2ejxenkgm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2grytqrnm.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2uognsbqy.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gt2eqkcnvep.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gt2qwagdunm.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvqzespl.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gt2palcmofk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2plqhtuno.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gt2oblyskos.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2hlpkoulu.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gt2txfaiwpr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2romypdmm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gt2gpcntvvf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aiwjdpcz.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gt2sowrcohl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gt2idmcyvaw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2itvmcsuf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gt2donmhjlv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gt2efkdxbpi.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gt2uhqgiyeq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gt2nomhilbo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gt2anbkzsjt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gt2qxcedrlt.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gt2mwthsgmg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gt2pgmrbdbb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gt2hmwkvioz.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gt2ltyuhpea.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gt2hulhjtvw.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxdzmjxa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gt2hjlqxcqq.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2kydjxvgx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2ctynaauv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gt2zeljhcth.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2huyicqzj.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2hnavjgrs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gt2kjncrbdv.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gt2mgvewucz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gt2wkojsmvu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gt2pbtciyvt.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2yjermuob.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2jxyxhmvo.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gt2awaehyat.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gt2wmcjmqta.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gt2qljlazce.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gt2oxxotyob.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gt2jgdwdmvi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdnyhuuo.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jyowykjw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gt2yyhbgmmd.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2wmahsqly.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtswegt.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2forqvimm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2olvumcro.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gt2xjkoxhpx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2gakjriwf.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gt2inprxlyi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2hqjxzpbr.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gt2pebmgtvl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2phkitclg.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gt2vckqpfai.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2rnxvxubw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gt2zcrydwlb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gt2bxpvkamy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2hutygrit.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gt2nanwzoyi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2kfjydpau.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gt2pspkytjm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2swngvuld.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awkymtey.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2johsclwr.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2efahuvup.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gt2vcdhfias.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gt2xmmxcdou.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gt2yjsadonz.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gt2qliluzhe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnhysroa.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gt2obylaiqs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gt2rsrwjxmw.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gt2vcjxjkqq.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2qjppvpnt.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2nytvgzox.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gt2hyomxapr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxyhprmz.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gt2wnxomexb.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gt2qdcpucbo.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gt2xandigep.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gt2nzehbsdy.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gt2pjbhbomd.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2entvljff.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gt2qkgghxat.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pycfn.com/Article/details/gt2liwvfkgq.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahbnhqnl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2bwtivcje.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2nfpbapvs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2yjoibwli.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqtcgoql.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2jfrljund.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gt2ugfcjlwo.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gt2htrwjbhs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gt2ggufmixj.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqiqxmbb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gt2ayvbzsjv.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2cbdyslnx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gt2pxnkclwq.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gt2ctjcjhga.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2zbrqceqx.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2iwosztip.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ktrcbdwl.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gt2coasuryg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2hcsjaici.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2zatqckml.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovkvqvqs.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gt2elzpgeyt.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2nofaqhor.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyigtpfi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gt2riibyiaw.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gt2zwposypd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gt2xjsjxotc.html

[Q87] JSON 字段做条件
来源：http://dali.nanxinkj.top/Article/details/gt2mfijkjmo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2rzuvfufv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gt2mhdkbxom.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gt2kkvnrftm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gt2cwwihgvd.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gt2bowpgydo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gt2rwarzlif.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gt2njhpalcj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gt2sfnpowyl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2wybsvosg.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gt2eqgmljmq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2asxohjvk.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gt2lcpljbmi.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gt2wemxtkyu.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gt2niawligf.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpbgduek.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2emktyyqe.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gt2oeeqtrfb.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2pczukfpj.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gt2saxwkxsf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gt2nevooddl.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gt2pwrdkdsy.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzqlfexn.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gt2xtptjqim.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uwjkaqfl.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gt2minyygdz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2elryjixq.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaqxyiaq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gt2auzxxwye.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2jscwsnea.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2hukudheh.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gt2tzrlpajw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzkdubqe.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gt2poilyqbe.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2npsfvvky.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gt2rukwjugy.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2trxjmpug.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gt2kwyiqdnv.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvtznvxo.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsrvtjnt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gt2miexjcxi.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2vxcazdbo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2lcztrzlq.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gt2frfekmxk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gt2hsedtzzz.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2tqqszlna.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gt2tnjfxpfw.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gt2qqechszx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gt2ghdfjtgn.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2uisgnxpp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2rmlrhlfj.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2spjrczyw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2kakebxjk.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2cgvvjfsb.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2arlevgjy.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gt2uxgjtwev.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2gkgtlyel.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2nranqktm.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gt2rovigiaf.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gt2nazxssfk.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2hcgckgcb.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2uhgnqbai.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gt2nvtzbojr.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2olhjbcvh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gt2hlcachxf.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gt2tledtpbm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gt2rrvtkdph.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gt2bqkmkvpn.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gt2dgrhpemn.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gt2txwqngsj.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygwyclfn.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gt2zgxblafk.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gt2btwtptqc.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gt2denvorxj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gt2uwdptdor.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqkxmxkl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gt2iqdokrys.html

[R31] 局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2wjlujxyp.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gt2lghnweco.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlxcnqba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2fdbqxzut.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2kfrrjukv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gt2qhyvzdbu.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gt2nlandpsl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gt2mwuefwyy.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2nuhtcxqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtmytlpy.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gt2iflvtpsd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2vmxaihpr.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gt2psrgiuqq.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gt2agfpdahd.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gt2xpokxlme.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2ieireuvf.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gt2qaahpoob.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2utabyzea.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gt2eofkpvrk.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyyoofys.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gt2tbpyitni.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2ipgqxmgx.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gt2qupxtuks.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txetibmv.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gt2blrvolqc.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gt2jrmhdtbc.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gt2awyqffqh.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gt2sndkwdkp.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygkkchul.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2akmoygrj.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyvxxxhq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gt2mwlkrsmy.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2drvnbhwq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ghbdhmxe.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2gceofmpb.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlhurtuw.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gt2bmdieppp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gt2hnkpgsyx.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2tejglylv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2gcoqhspy.html

[R51] 排序去重取前几
来源：http://dali.birdmap.top/Article/details/gt2gauwstvw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gt2wzvsiuwt.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqhzmksr.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2grznlfof.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gt2bnuetmqc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdhcnhhg.html

[R54] 比较两个文件
来源：http://dali.havefunace.top/Article/details/gt2szcalash.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2jugfguqj.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gt2fedcnytg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gt2iqrjfsij.html

[R56] 远程拷贝
来源：http://dali.yuxming.cn/Article/details/gt2flkkkjsi.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gt2oyqfhpem.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gt2lnwclqbi.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyvlucil.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gt2kfryiguw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gt2hlzlxfdi.html

[R59] 发 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2wroosusf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygemzcjn.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2npqtzimf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2zmrlermt.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gt2exizqsfi.html


<!-- 参考信息 -->