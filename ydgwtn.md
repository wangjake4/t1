代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtrfzlrrjq.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxnecgdc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtovqshrrc.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtzpqjesfi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtfvtdqdeh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gthxtvgnfw.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtfhzjcgjq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtldtojjag.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtflgijhdt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtfydxhksh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtnqnmrtai.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gtipfzordi.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwyqwkgzh.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtpwdcoxje.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtyfgvfifp.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtratbjgrx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupuwsgcf.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtyllykzoy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtkdpvxdvr.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtgykwfkvs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtmgjxhiec.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtakxbkebq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtoiikuhhn.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtdcmlqmrj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtgnpygjur.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtzlnciarz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gttmhcewro.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtjslnzvrp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtbzwbuknf.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtymfrnyqu.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmxsyblke.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gtjmyrxtnu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtmtdmmtxj.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtnxvwwdpp.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtpxrorhwn.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtiibswwka.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwjfezbwx.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtncaqfxvq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtukcxqvic.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gttgmusaqs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtghuurvpi.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gthundanrz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtnusiekcc.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtnbjycifn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtearwdejh.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtzluipqkc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtppbqjniy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovbtmdhq.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtbruslyzd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtwrzqndql.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtakojbhof.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gthpnsmbix.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtbnufvzfm.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtmobmojam.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtqvxbvfeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtlgsjynta.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtufuaemth.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbndenxzd.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gtehmelhgv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gthhixfyby.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gtkqavcxuc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtebmkwwbs.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtgtvhilmp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtnfkdobaj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlscaeiwd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtolsmqsov.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtytrclihw.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gtndvzlwdf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gttbehivhf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtgnkufekt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtrmiljarj.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gthxrhidnn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gtefczdqtx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtqgvrkmga.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtnebjnjaj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtedtgfkfs.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gttidrmpmy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gtbigowrzr.html

[Q45] EXISTS 判断存在
来源：http://dali.smart0.xyz/Article/details/gthpajwcrh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtryblprhb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gthnjfcodl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtsenoqsce.html

[Q47] 与平均值比较
来源：http://dali.sweek.top/Article/details/gtwmmwboua.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yueranfly.top/Article/details/gtkehhdczs.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtwuvvimsp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtlqfbzdnc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebhlextu.html

[Q49] 更新单行
来源：http://dali.yvedp.cn/Article/details/gtosvdoefs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtujdctwoj.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtwxvwjkii.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtbvjzijfr.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtgappdjvt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gtdfbzksph.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmkjjqii.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtkyjvevhe.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gtpagsocfk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtgutbyxmt.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtntgzemzu.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtuhhdsoka.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtrtvlvceu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtbuaeuxpr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtcpoofgeu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtkbdkkhaa.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtxvtabslf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gtujmnkemk.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtbuxctxuq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtbktjbaap.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtvyumxsdw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtdvfhvdaz.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtckhgjukl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtwfzdrfhm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtadblpbno.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtsohggzmn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtymspjxna.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhulhkls.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gturqzzvmr.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtzwwaegws.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtanqcunbp.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtoblopwxp.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtsnhprxcc.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtqnuarhhg.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtbzqpynhk.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtzqjjocvl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtsxhjevhf.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtkddnrgip.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtfnfmhotp.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtfyigcaqn.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gtidjesmcg.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtrnlfzkeu.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtojexabww.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gtwqxezgun.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gtxaohswqz.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gttdzqqkgi.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtyoldatbf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtoborxbvs.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtwhkodvrs.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdsmyljwe.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gthwsajcgk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtafjircxf.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtksjsojtv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtaiocsixy.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtombpivxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtozfdigzb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gtfpsmhvgc.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gtexpcqtdo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtljdcftqi.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtpmufgeco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gthacuuyee.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtjuulchxh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ehwqpu.com/Article/details/gtelzkdbor.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtrogjxkyv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtdmioqlnm.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gttzfshqkl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtmgoylrfx.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gteamoqvds.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtfkaydagn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtkpgbszpf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtgczxqxoz.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtbubckalg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtuedvynxc.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gtsvjemjfn.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtoomiorvz.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtgyksfbuz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtevaymxxi.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtzdkwcrrs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtqoaktwgx.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtleesrfcw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtbvrjrojy.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtbaawiyux.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gteyfgkdtl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtbiczihje.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtojsidaei.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtmftmscjq.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtlmqkdehw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtpkivenlr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtijrxglbp.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtwpxhbdqu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvkoedbc.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtqtholadu.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtahxsieph.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtxegntzms.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyvllsxu.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajnkgtjw.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtdrajvgea.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtjdeschaz.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtagofvyhe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtcvlbyama.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtnylwofzh.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtvoxxdlqg.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtxovbxamh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfeguvrax.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtqfzltywv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtkgtumouh.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gttbccelvq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtmynpjpyz.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtcsvqdiyx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtinpwfghk.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtjxzxafkw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtagxcstwq.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gtczeqppuy.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gttfygwknf.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtbylaxknp.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtqulwuiid.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtsonezchb.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gtwudqwarj.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtckqtnwuq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtmlplhtan.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtdvmbxzjg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtunsyzfna.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gtattsmqzo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtynehacpf.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gtjkvhzrcr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtbrxljoup.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtsqwwtfig.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtabonjtqt.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtovvecsyh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtdpapehsu.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtlydwyerq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtzcfdcjiz.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtlvkappfp.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtccstsuoj.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtoifguzez.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtmjxzzeic.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtpgjzowgc.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gttuavmjfg.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtghvcnnps.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtihltwnxj.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtquhtkagh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtfeminlfl.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtzemcxfwc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gtyagqoxhk.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtmlruuggp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzloivadq.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtbzxtgxcp.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtihdztyfr.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtculvhpoh.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtmwvencyp.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtnzvcvibl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgtascee.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtuacgenau.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxuanxn.top/Article/details/gtdyemmkhl.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtdnrbtfvf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhixingplan.top/Article/details/gtnjhduoeh.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtgrydksfr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gtqdggshmv.html

[R32] 参数个数校验
来源：http://dali.xuetiantiany.cn/Article/details/gtjrrtbens.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtuslptmqu.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfnuipzx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtkthnsvpq.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtfthouubz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtoeqrukbf.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtokuvvbix.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtvlnriixj.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtlhywazpu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gtuycrvyef.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gtpmhfuycu.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtadyqkmmm.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtczuukmac.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtgzakpdjo.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gttnjttbkz.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtpogzrdcc.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtkzoejlkr.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gtkjogugjg.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutbkgtng.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtmsfiqdvw.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gtjearudkz.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gtutqfixds.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gttwriffbr.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtytnofpnq.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtrmqerfgw.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtvtqqehlg.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtkpgfhfiw.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtqhgvgths.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtelbekccp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gthjwqegwi.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gtprhbjwwp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtajfhnvyn.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtkfumpnpe.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtknbqfqfj.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtjwwzsdwz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtlmmapudu.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtqhvmkdzz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gttjxwauka.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gthnsjilxd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtqfakmany.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtxluwuptw.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtnauoqvhj.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtbxtbnlcl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtcozgpnmy.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtfyufscuq.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gteoifqktl.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtdkaxfxsk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gtidksncvv.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtwsrgkqif.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtootrlrxa.html

[R57] 远程执行命令
来源：http://dali.hongshengwenyu.top/Article/details/gtyxfwozep.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtmlictkfx.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtqfqeyncz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtxqjejqrc.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxofjhqwu.html


<!-- 参考信息 -->