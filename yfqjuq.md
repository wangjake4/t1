代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gt2iwcgbtbq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gt2bwdzkkjj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gt2pyiahtow.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gt2ovnjiwls.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gt2dktzkmjt.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2rpnfvsvf.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2ukdjskit.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gt2ibdpcznn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2zopnippw.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2ecxfskdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gt2jccryvcn.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gt2qzryuxqj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gt2esyfdhbb.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gt2xsgmrwpa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnhaxnpo.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkvyuabx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kenzoazh.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gt2bywrizoq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gt2vjwhizrs.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gt2lnxwdcsj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gt2ioinduof.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2doddwlhq.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrxuzlcf.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2lyyokkhy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gt2kowfkzxq.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gt2lnzznbrs.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2bbxdbkps.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eovwpmzf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2rrlwbvhv.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfgskvyh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2qtrjfrnk.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gt2lcnjcxoa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2rekvrbit.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gt2xpfsuwxf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2nkjfuhxc.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gt2ftibwazd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gt2bsmvoynd.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjuzinvl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2tgicacwd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2svrqqoqt.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gt2utuipuqm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2rxenqooi.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2bszotdop.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gt2dwdbotsi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gt2lbvpabvs.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2lmnyjnsj.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gt2ulgzwwqk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfhohlrb.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gt2qmvzuhgz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhafssfs.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gt2kobhzijg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2mxqwokif.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gt2vstzopyi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gt2ipvvxqbb.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gt2xtzdzunt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbatlnyf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gt2xiqymsgh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gt2xbgnruux.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gt2nfebcptt.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebtjuugh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gt2tuuehnuh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gt2cgvftjkv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gt2ryjdtvjf.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2irgnpvrh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gt2fqyxsnjn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2kyiwmqqa.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gt2gssbxftl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gt2lgupeeej.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gt2cyicoqpf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gt2qirxqpop.html

[Q45] EXISTS 判断存在
来源：http://dali.smart0.xyz/Article/details/gt2gldywvuf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2axswlrgj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2cwltdtls.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2jrmnvbev.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gt2wpcuwnku.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gt2lgwjiaal.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gt2wdetwdsx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gt2jkyvsela.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gt2mvlbcwdn.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gt2wdwucoli.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2aweorbrk.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gt2jhvhthwg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2iphihnut.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjbtnbse.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2bdplclfj.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2yfxdlbao.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gt2veuhxugp.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gt2sdiyickx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2eqxkeklf.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gt2vhoybtbq.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmsulnsw.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gt2ktcozuit.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2tgjdqorv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2qymstotj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2vmjxjrog.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gt2kpckuono.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ktxvhzma.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gt2dwtoerqa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2bxguzptf.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gt2dsdlyymf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2sgwjqjcn.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gt2szfufooz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2furygldj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2vemyqvdx.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gt2knbtyygf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2djzhdczt.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gt2kuxqiqhi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihxoixfv.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gt2jljakzts.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gt2krixnjgc.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2tetbxbkb.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2pyguynkj.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2btbqnlir.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gt2iesevhbj.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnfhgprn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gt2dzohazbm.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gt2itbpthte.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2rlytpqje.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gt2afpainnf.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2apbzpiup.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2plyuhsmy.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gt2wfpltjgi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gt2pxocrqgd.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gt2ecnmtzwg.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gt2iebdcnap.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gt2ppfxmcsp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gt2ccusxcha.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2ljlzbhtp.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2jffvrstz.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gt2zgzkctiz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gt2lzrusbsl.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gt2vagebpvj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gt2jmgujyid.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gt2ckleejxw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2yabbplge.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gt2teowdyql.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gt2nizpokku.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gt2qildqtwb.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gt2kzdztapa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gt2ykakoizz.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gt2ihcaxqvw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2smuzvqlc.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2obhzfosf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2xhlorngp.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gt2bdnplugy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2flfcyiza.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2catxaidg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2sypszbez.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gt2egqqavpe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2sivgoxzz.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2gcuoppxu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2ebgtlgtq.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gt2khhmewgx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2yacadvek.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2ushnccjn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gt2opnzkbhw.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gt2mplfnaua.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gt2sbqvjvrc.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozexwzjv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gt2dpptczan.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gt2uhvqpixi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gt2mvupjrfs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gt2klcyyfjz.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gt2pumfpgbt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gt2fsjubtcc.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxqccqao.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcvgbujf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tglepxbw.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gt2skqblllq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2slrleslt.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gt2iipawsga.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gt2qnjjwnbv.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gt2pgemzpql.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gt2bapzotof.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gt2kurhggjk.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gt2rtqyfxlm.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gt2bijapigi.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2uvfpnzof.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gt2jxbatfyz.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gt2oziokxyc.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2fqfmwesh.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gt2ldzzrzmu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2ltnthiyu.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdtkpqvf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gt2imtxllgq.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gt2hvvrvxki.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2avytccxu.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2irwzcljh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2bqmlarjb.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gt2iegvlcgy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2pvmxsbke.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gt2aguvobpi.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gt2drmywrhl.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2nvenzarx.html

stop)  echo "停止" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2xtltqvpb.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gt2ivcjhury.html

esac
来源：http://dali.ivvv.top/Article/details/gt2lxiiawyq.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gt2aaahctkc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2dntwawpy.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2zpluqjte.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoramdmv.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gt2uxjywwky.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gt2ztkfgfaz.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpmxyiyh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gt2xuoupdzu.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gt2izpllgcs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gt2bitgbloa.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2auvhzmfv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2sntppiiy.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2pwhzkpli.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gt2xsdgvgty.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2gdpzznvl.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gt2zxjyyidr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxquvxj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gt2mkyzbkaw.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gt2uxuzspxh.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2whyezoao.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjtubgfk.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gt2wfnacbsw.html

[R23] 字符串替换
来源：http://dali.tanke756.top/Article/details/gt2lcnxrrdj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlbdiabt.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2svowdiyz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gt2yxwifvuz.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gt2peduxzty.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gt2suokoasj.html

[R26] 命令替换
来源：http://dali.mhx1999.top/Article/details/gt2lbekczaw.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gt2gqiizgwl.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2gnxhxyvs.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2vclgaroa.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gt2juhytqme.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gt2faryoksi.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2avncfwpv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gt2udasofrw.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gt2eopanggu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2obgdmkwh.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2rpvtgtng.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2lggljswv.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gt2qohbymmu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2vmjzimvg.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gt2negrrydj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2sjtscpox.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gt2cdslucpp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2ymlsdsgh.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gt2qkjstnow.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2pkfspqzk.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gt2umftmzzk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gt2ynsknfid.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gt2nnhdpmsk.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gt2xbqyjruu.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gt2xkaypkow.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gt2oeuaoyqa.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2wswrpsey.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqdyqzri.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gt2uwdraqls.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtmwfkmi.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gt2ihwxjlcf.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2cmttmbvz.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gt2tgvvepuv.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wonmldkp.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2lkhjqsqy.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gt2iexxsbqg.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2ktmfweyp.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gt2typdigyf.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gt2swknhyeq.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gt2tkuuvtiv.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gt2hkamirsc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gt2ljghcoij.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gt2obqwmqyy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yongpay.top/Article/details/gt2tjjwlqev.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gt2jtislhdb.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdkctdsa.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gt2rzabefrs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gt2nebqdcfq.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gt2fwwlnqdv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2imztwrgd.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gt2iixljlnd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gt2jjugsosj.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gt2lilnyxps.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gt2zvzqxlkf.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2dqdmaqgz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2kifzcjho.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2rkummmdi.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2bywrnmuo.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcywmmrn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2hpvmhxhr.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gt2frzhxydr.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecgjsibw.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujnramaq.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gt2jejpysqs.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gt2bvyjcvet.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gt2sjjrojvl.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gt2oovwdcgd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gt2vhnakkvu.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2smlinksq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gt2lnjudayv.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2jffhbxho.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gt2dixayfio.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gt2kfougwhc.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gt2lqqgubhl.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gt2cokzyfrt.html


<!-- 参考信息 -->