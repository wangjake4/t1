代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtxrqkisag.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtolhnpvmw.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtrpvhgjzt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtfqctuwmg.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtyvduoavb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtzbmbwsaa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gthnsnsbxn.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gtqekoxrcg.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtolebnvjb.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtmxcuegmv.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtchyndndv.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtjsbiggbj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtkjgyftzm.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtscfpsiur.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtslyszloq.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtdkhibpyf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtgoqevdii.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtjopqjarr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtkszfjgpn.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtrsuyqpgf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtfkqohkrb.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gtbwevgbba.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfegrcfjy.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtxmhwyndj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtybktdcci.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gttqgctbyz.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtsoblccgy.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtwvrkalqf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtqvxgsmjh.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtnwirrasy.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtougawwfp.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtemrqzwpu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtehdddzwc.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtggrzbbrc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtyzwrkixe.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gtipdrpbrk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkefozyd.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtliutdthu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtnhvqirwc.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtefrhlzjs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtijowekdd.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtiqixezdh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtqeirxfyx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtrfloodam.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtpdnjvtkl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtncdqvnfo.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtsthldpqo.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtovoipgxx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtpwxrcbhd.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtatiszirf.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gtrzghghmi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtoqnwlqyd.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gtlrpqmndb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtvpmuvxel.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtqgxwakux.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtexbprnjx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtaracepbr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtrcegyotv.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtxkwyfivc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtmbvveszr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gttvsxkjmu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtvfgztnft.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtkovcbbob.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaickbtwx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gtfjyunvqi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gthdtmewwg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtmedgtncy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtfkbsfohk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtbomqsuoy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtgivifpnz.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtjpovnohl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtkmvdkpwc.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtdulncror.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtfpdyicif.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gtbrrmywmx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtnltyskhf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtdnjxjbsr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtcdklruyy.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gttygnfszv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtebiunnkk.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtnpjqinea.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gtdetyxupw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtrivrpxgu.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gtlglhyodj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtwudecspc.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gtlfvoueaf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtofxoyzav.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtjjhdpcgx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gthbdmyxly.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtsjzfkngm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtawlsdjyf.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtthrgxacr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gteceontgb.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjcsfafc.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtahwytvqb.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtpwoworzr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtqfrrgkub.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtchxoxxxx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtbkrkncdh.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtdgltytxy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtllsqphhu.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gttddrljzj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtflmoherl.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtpumhvzpm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtrqaenpxh.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrodiqflx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtgkvxcehs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtqhnmsckk.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtukgtkopw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtawejufus.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gttzixrxmn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtrjhngyam.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedjancaw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtmrwmdvke.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtekbjpepg.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtoaaclbgj.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtxdnwfkjl.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtcdsdhapc.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtvqmxvbbf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gtztyezwsp.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtahreivua.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gtwexsdgic.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtujljvzyh.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtpborpvnx.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gtwgprrcjn.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtktykxyvq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtettjnkzh.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gtzehesivh.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtavjqyoxt.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcwhqype.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtjcjrtxyj.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtkuvgnqak.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gteyzyjaoe.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gtkjlliyzg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtfqanpiru.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gtwwqrakwo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtzclpaxfj.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtlfxqypnb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtwemtmovf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtejxgfdsg.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtcenxugmo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtidqiqbhu.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtdygenqll.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gteoioybfe.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtjydmgjki.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtrkclzwdj.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtfxtyanav.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gtpiuixvyg.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtyfhxigea.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtbzpzdacu.html

[Q81] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtudfozfsp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbbrqknba.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtkmvfrqjy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxaqygjcl.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtoemyhjtj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtzzqxlggg.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtvzkqvswr.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbnlyhedb.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtxhohtykq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjywguly.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtflxnnwhu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtzzohutuy.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtntfdcrmu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtudfenwbx.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtrvhiylgf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtaelkvjfe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtpkxrgduh.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtnebpcxqb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtevtzneyb.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtshpspwfs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtvaxmskyo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthrxfpvra.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gtawpunrfj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtblpchnsy.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtiikvanui.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gtimyxzjdk.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtknaoimlb.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gthdttkhst.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtlmcvivqz.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gtxckxatav.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtbddirzxv.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtueberjdy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtuycxqumw.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtopmviyij.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtglkvqswi.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtzniglkcw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtmydbutvh.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gturztzmna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtnflcsuif.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gterkosdrm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtzddqhtrz.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtdehzbgqh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtvlbwybpb.html

[R10] 正则匹配
来源：http://dali.nwbrower.top/Article/details/gtwsdwrlvs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gtbhkkqpcw.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtezxxbzac.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gtufnlenjp.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gttlwjrgaq.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtwvrcgscv.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtnfwkgnuv.html

esac
来源：http://dali.cucudq.cn/Article/details/gtfksuchgr.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtyzvkgjmn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gtnqzijijz.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtisqpalsw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtkxzplhtj.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtonbwvors.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtqdkcotii.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtrkgmsbsx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gttnlsypvz.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtromkjyqg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtnltlkcjl.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtrwdphjnq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtsautbdds.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gthdkqrbmm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtkwsbgbue.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtictwzrpa.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gtiiqrxgtl.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtgavrjuoj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gtrlelyavw.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gttaaddthd.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtauiavqyw.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtfoqpyhnl.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtwqnhdevh.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtqnjsifhn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtioqwrdil.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtvlvlchpw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtligqttjp.html

[R25] 去后缀 / 去前缀
来源：http://dali.xinyue.icu/Article/details/gtaocqajev.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tianlin.xyz/Article/details/gtmbzkasts.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtwoewrges.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtojyzyerd.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtmjngxlkf.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtmwbresow.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtnzigtrzn.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtczizfszi.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtsqgwpytu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtkpsxigbe.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtrqdnanax.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtbmfrurak.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gtmzfihmfq.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtzttlatpw.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtrmxfyihk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtzvnhcwrt.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtpxutrywd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gtzshbsaqb.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtxwmgwkpz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtjhzycoke.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtzscfodth.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtewlprcpl.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtqxrfjwfy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtshrmioiw.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtkhitglsj.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gtsfglnjln.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gtykomprpl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkivwujdh.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtnozunyig.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtzehqmlkb.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gtjhtiaquq.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtubdbpore.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtxibqisow.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtetxialcc.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtvnyubvpo.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gtajwxaiie.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtgeqxswgm.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtbzmhdczi.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gtcinmatrp.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gtqxnkclox.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtqkgdwmfh.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtbubozpvt.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtpwphxkvc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtpcvqttxy.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gtzaoahvnp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gtxndcsbqp.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtfxlclclm.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gthwqnhcpf.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gtxbpfbyzw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtbmixmeyb.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtaaertrzt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtzrmvszpn.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtwmbflybm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtobjcendn.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtmjulyqua.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtatvirrgu.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gtbyznyvzn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtjqldgvmr.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzciassuk.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtxoanqqph.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtnlhybedr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtannlcvix.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtheddykkz.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtpewlknzp.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtrygggtfx.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtewpeqnwf.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtqxcezrbg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gtbxlpdrda.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtsvcfeokl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtrxnkbaut.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtfxcpjckc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gthhonvgfj.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtmuzfjquv.html


<!-- 参考信息 -->