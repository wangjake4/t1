代发 wailian999

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2ygatthfe.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gt2ujnrbyhu.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2zzlhbdlu.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tujmgybz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2mwlpepvq.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brgixiai.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gt2tanmxpqa.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gt2vyuexico.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gt2tggwmfki.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gt2rdibslzs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gt2zivanfza.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gt2dzprhjtt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gt2fktbawei.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gt2nhncygpp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2djwbqcfm.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gt2rargmbth.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gt2xhhuhzza.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2czwbfjvg.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2tlhrymvs.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gt2piogcjca.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gt2thslrebz.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gt2empvbakp.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ydtkutof.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gt2guowtwyp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2tcufechj.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gt2ouzwckei.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxqdocwf.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gt2vfutisxp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ecsghbxo.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gt2jtvoqmet.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2fhlsvqse.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oywwaoxo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikxqlwso.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2gppjjfjx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2wlhbqjbk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2uxnikuhk.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gt2fwijuhkk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnzbgcns.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2bjzwpizh.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gt2yhmwbulg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gt2wdafaljg.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gt2bgdwygow.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gt2qgpmuipz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2nfyhfwvn.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gt2wsergcfs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2wqpvogrq.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gt2cbzqnoxw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxodxmas.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2lsnngpjt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2bkcvtcrh.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gt2wlpiksrg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gt2rjdeoora.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gt2mzilnywp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vouuwpxu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gt2rlnptsew.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gt2wzuydeqc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gt2bzjbzxvm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gt2ehuspfkw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybqwjpxy.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2kuomerju.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2ssuvxrod.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2kaiedsgj.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2qurmmbvm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gt2qipzhkqc.html

[Q44] IN 子查询
来源：http://dali.snrcjt.cn/Article/details/gt2gmdgrghc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gt2zovilxai.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrkgmsgt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gt2spmomznt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gt2mlzsvfmb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2fbthnjke.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gt2hjmakxei.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgfabory.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymkmveme.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gt2wmxpscrt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2pwhnesuq.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gt2khngbvnr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gt2hehcmztr.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gt2ycndhfne.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gt2wvlzfahd.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gt2lkbyudgw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gt2egcwipve.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gt2rfuoakca.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2racqtqdn.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gt2qeizuhuj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2awglqocu.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gt2wjoqjsyk.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gt2ykuxqfwv.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwfiebdx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2czrzwfcd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2cpydrdmv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2obmuqjxl.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gt2kreyvgca.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2imqnxmhi.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gt2kvbbumnd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2ptjsbpff.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2nnpykzgy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2dunfyrqh.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gt2futcfmvf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gt2ufuneunf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2peeenrtj.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gt2meihnfoj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2jmjuohvq.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gt2mowohehu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2enatohpk.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gt2urwougfx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gt2uejqzpma.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gt2fzxiezbv.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gt2ylxpmigy.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gt2irtjrejj.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gt2kemgastp.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gt2lkxwmfwe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gt2eismqvlg.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gt2mqifdxan.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gt2niatdseh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkrcyrc.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2wijyoqhe.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2agzjsmtc.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gt2gpjtnnju.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssuxjxvk.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2gvhzsqdf.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gt2vrmqrvap.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gt2dhpgahos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gt2trsjxehx.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gt2qwovsjti.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2dxxcgiab.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gt2mdxdlavf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmudflcl.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2wusxgdzd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gt2czuonniq.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2uecgbqlh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2ulpgwdeg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gt2slwvzmbp.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gt2fzvihxjk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gt2ijyawfpt.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gt2niktgbmy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gt2nmrgmrop.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gt2tgscgkdd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocekcoqt.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gt2pyvbiwzx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gt2vavntuwd.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gt2fkdbzfws.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2iaxnwsoe.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2wdbxzmve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2gwygjhch.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fehvsqfv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2cjonikda.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2izwobtgh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2gbijnycz.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gt2dbpsfvvp.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2kseagwrx.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gt2mbbgotob.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2umgzgxuy.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gt2tzekfolj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gt2qtdiozmw.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gt2vyyqoufn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gt2mkqekece.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gt2ybhhwnnj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uskynbtq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2afwkwlxc.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2pikyjzta.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2noptvifu.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2sznpbgeu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gt2croubhxk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2mebnmwnq.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gt2orjaabpq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ybkoaqxe.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gt2ceblzhnq.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gt2htfpxepl.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gt2dinribal.html

[R02] 变量赋值与使用
来源：http://dali.redwolf501.top/Article/details/gt2izgsolvg.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gt2skzotjgt.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gt2fxxvvdva.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gt2botdzrtv.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2uplxmqui.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gt2pdsofzyq.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gybnnieu.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gt2knrqreja.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipyvrapk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wlrhtqua.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2bkccjmkh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2nwoalhcw.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gt2hkmkhula.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2vvkfkzrn.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2zaiwneuq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2vzqhuvmn.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2lvbubxbd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gt2zjlkjkba.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2dlkjwhzo.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2ahcugcgt.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2xrnjbkhs.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2qbctahnj.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gt2gdlqkfpt.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gt2qssnhyvt.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oeeszmde.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gt2phbzdnvc.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gt2egiqswer.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2tlmzwsot.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gt2ceswxwav.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2kfxezknv.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpldpmxy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gt2cvggjmsv.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnwfdfyg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2qfzyagjl.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2denetaah.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2rxghmuzu.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gt2yrtaarrj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2zipebesc.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2turekmpo.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2todeefxh.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gt2mzmgbqxj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gt2jcqhfbxv.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2lcchhzem.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gt2wqvurwey.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gt2sdqfrygs.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gt2gnzfcyep.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2lssgzwfk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gt2bfxjwpjl.html

[R24] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoxpkpgd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gt2kqbylean.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gt2tawrqhat.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.svipenyu.cn/Article/details/gt2xrcgkvcz.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gt2mbtttdza.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gt2gslqilrz.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gt2zkfyulyv.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gt2tjwbttfu.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvyhlngt.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2kztfqnvf.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2wfdqimcs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gt2mjhzhsyx.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gt2gujydzng.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msowsvik.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gt2lfxzlltc.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gt2icysljic.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2zxobvtdg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2lfknsgme.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gt2npuqqsft.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2ikboyaly.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2qzrdoixg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gt2wqhubqdn.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gt2lrrjwhub.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnwllnyt.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2pllxgfzl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2ytonjfxs.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gt2unezfoye.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gt2xjdcnunz.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2hoxrxrbs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gt2yygxbbai.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gt2rezojqpc.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2jgjpzfuf.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2qkpjdjtd.html

echo "log" >> out.log
来源：http://dali.chenlongwang.top/Article/details/gt2cwukzfjz.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2hccofokr.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2ahllqvqr.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gt2hpuvzlwu.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2baeujkmo.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gt2asitfxjh.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gt2flrposon.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2xeviufgj.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2nzztbeay.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyzwnude.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gt2wqwpddqd.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gt2ouwruytn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gt2vvljnqsr.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gt2misljqlv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yongpay.top/Article/details/gt2nztnrbsl.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gt2axnxswxy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2razzwtyt.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gt2lwitfygv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gt2upvjelax.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gt2szjvtwiv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2vgsqkwpq.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gt2adkiqduu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2uxvecffg.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gt2epiybxkc.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2amlqaxcu.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2makekswl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.meibo888.top/Article/details/gt2hcoceyhn.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gt2tqtdsiee.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2vkkpyosl.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gt2psspjnaj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltsjwluu.html

[R56] 远程拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtkamtnl.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gt2fmdatqif.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gt2wmhcfeez.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gt2omwpzsyc.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gt2ssmzgghn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2ejsjmohe.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jaxuuldr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2vducpytf.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2acbyykhi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2fddxfjlh.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gt2tomhyedl.html

df -h;  du -sh *
来源：http://dali.hnxiangtu.top/Article/details/gt2neltwrku.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gt2vmbvmruu.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2ucnbpcus.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gt2xfgvxahx.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gt2hfmsxmhe.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gt2sxqggsyb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2svwzzpil.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gt2acisdtht.html


<!-- 参考信息 -->