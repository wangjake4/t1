代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gt2gmjdptts.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gt2nzfwsyff.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gt2parwfujv.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sihcivkm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gt2bmermsqj.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gt2cmxxoayp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gt2dyjahtue.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gt2pvxarols.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gt2cwzrkauj.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gt2egfcrgkz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2whqqemvh.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gt2okzaxowx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gt2grbcmprm.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2klyvlbhx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2hukjlneb.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gt2rrrcahlp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gt2xjlfqovm.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2jewbfbbq.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmjdoiaw.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gt2fanptnmd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2xlcqcgws.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhywihbk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rshbgeym.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2zbvnbaqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2yzboyued.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2hruxzwml.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2bgnifxkb.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gt2lluqeqvy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2shcjxfus.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2byreiasf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2qmaaghsx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gt2bnknfyrg.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zuqcbjee.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ludiumbz.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2bhmyqwuh.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gt2xzejzkfz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gt2znzvfwse.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2wgrmvecc.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gt2ujcydqsd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2lugvlequ.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gt2cgydwuij.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2qylxgock.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2ngruodwh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gt2mpcvudov.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbcfvpwn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gt2ykwprlhx.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gt2xsalwxmz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gt2uwsyjwzo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gt2kzunnqyw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gt2dhumrzwd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2fgueqiuu.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gt2dynsxeap.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gt2bembfoka.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gt2fwiszhbt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2zapxkuqn.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gt2nzqhpbqb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gt2bopjgqqp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2ldvqehdm.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gt2tipocfmd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gt2qlcnzhcf.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gt2awkspdcx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huwbzfcs.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gt2feowlfzv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2aviljyvj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gt2cgereiix.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouyipaxi.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2rdqperls.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gt2opqhosmg.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gt2zarospzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2vxuggdii.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2dvhrsfhk.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gt2glgmyemf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2qmsyfgjv.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gt2nybvcaal.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2npoklzjo.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gt2eolsbogu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2wsjzjgmt.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gt2ntfblfzj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2ujkeumca.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2tpmnjglh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gt2aqwlahro.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gt2ezmehkxi.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gt2braxunpz.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gt2zjjrjddh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2zbchollv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gt2ibfypndy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2glerxaxm.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2ujikxdbo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2aszoyqkb.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2azwhokse.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2abgsvbrb.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gt2tolnprax.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2icfimxqt.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gt2nnmxxiot.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gt2jksqnxkj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2utxghbhv.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gt2oymjegxg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2prwfvthq.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gt2cxnqrsik.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2eerlejzk.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gt2kzpmofpk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gt2wotfrngu.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gt2ipxndclu.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gt2kpivxbzj.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmcqehba.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gt2rhtjpliv.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gt2jrfubycy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjkegkiz.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2ixcoovfa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2wcbxfdjp.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gt2duaxypcf.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gt2sfavyujy.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2qecuerlk.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gt2mfeujhwb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gt2purxdnxm.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2ssfdqmld.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2mzyukkhl.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2ovptuiav.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyujqvox.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gt2mxpwtjin.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2katmydco.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gt2tjibwjre.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2dgamhbvw.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gt2aidfalrz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2znujskxl.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gt2dslmzlum.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2tatyoewv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gt2cufqjxbl.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gt2jduiqndi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzusitpl.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gt2tyqaeiww.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gt2hnrbtdkm.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2gslsdvaf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2vksmwnfg.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gt2bcqtfyon.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gt2dhldumbj.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gt2glkwsxmb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2oesmstkd.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfjidqfa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2xgzrbobg.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmqqzzle.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2wryfnpvo.html

[Q83] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2vpwgiaot.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2wcpditjp.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gt2dcpdzoft.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2gsxiptfa.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gt2phsvpllh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gt2liiruvdd.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gt2bvqzeoke.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gt2acizniyd.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gt2izcwuuhl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2zrshuhpo.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gt2tkpvwwmi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gt2lixnsykl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2niscksdn.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gt2qvrdkqqd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2ssmkrrjy.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gt2nvisszpw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvgdulwb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2czmquywr.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gt2sjjwefvz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2pmlbftpm.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2ojjqjuwz.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gt2oxyffqja.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gt2ykfdpjlh.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gt2vymegpmb.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gt2ngxugman.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gt2zudxjudy.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2qmkgctfh.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gt2jnisloxu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gt2dhqaglce.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2wjdfujcd.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2ilmmqmck.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2karhatws.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jsosbyps.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gt2vaxvkiet.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2rqxlkfns.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2awxriduf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gt2tgeatwzo.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gt2sgdfzfap.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2vscfttca.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2cknhousq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2dqobcfki.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2fccrbzyn.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gt2zatcbtyr.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2vbtvtygl.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gt2ntxlgbca.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggcdjavx.html

esac
来源：http://dali.nwbrower.top/Article/details/gt2dswddlhx.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2cijkmnnm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2ofazbeyv.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2hbpsdcik.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2rxvsqsis.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2ghfdeytc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2xhbhlmmj.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2omncottg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gt2ftzkichz.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gt2fvpdjsbg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2ebczgxev.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2qiwckzlr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2gymnyzwi.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2qkyyfejs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gt2qjqifckn.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2ullpxgwl.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gt2zhnaijay.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gt2qmhqumzu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2beumiykq.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2lafjfbpv.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2pfkphfub.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2axtlehly.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2vwvrzbtr.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2qtrihdzx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gt2dangtues.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjwqnjbf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gt2ybsowhen.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2gjdttwgb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gt2vsgzruqo.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2sywwipuq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2xnvhjpwo.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2jljxgwgy.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gt2deewxuvi.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gt2snhoqldv.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gt2xsjbwfmt.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xvzadnjk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gt2ovpvfhne.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gt2buunbwzq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gt2gpfgjgom.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2synvcnqi.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2obvujkcs.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gt2qotewrlc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gt2katdwthi.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gt2mptahqai.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2saxnrdmk.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnxiqgjn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2sojcgsur.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gt2lvfjwfvj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gt2xzimpgsj.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gt2ulnwfnnz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gt2whpzvwwx.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gt2fwvybbnj.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gt2xsertefa.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gt2bhesmjgf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gt2rswaodwo.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gt2tbkbixgp.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gt2lhrmxawh.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wndfbwax.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2vkuefagb.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcwgmiux.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndotedsl.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2tgeboina.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gt2bsqgltom.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gt2yuetzxbq.html

find . -name "*.log" -type f
来源：http://dali.zhengqikj.top/Article/details/gt2tmxkzhpp.html

[R44] 按修改时间查找
来源：http://dali.yonumen.top/Article/details/gt2tyfrmlvm.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gt2gbdyjqdq.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gt2ppmwdfca.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gt2ucxywjzj.html

[R46] 递归替换文件内容
来源：http://dali.mhx1999.top/Article/details/gt2cpauzdbo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2nkztfobe.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gt2zczcchna.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2shltxfci.html

[R48] awk 取指定列
来源：http://dali.jiagoushi.top/Article/details/gt2kxuziiih.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2plnxfykq.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gt2dnxnilha.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gt2wqqgsoqw.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gt2yftsbyaj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2afsarfaw.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gt2bskeytum.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gt2viogmkqn.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gt2trdbjsfv.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gt2fusebuoz.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gt2tvzeldvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2caabklrh.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrutulte.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2wqrocgii.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gt2qlhwxczv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2iqpnstlg.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2rjdjedos.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gt2vqajgkvl.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gt2oishsonp.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gt2dhtaexhg.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gt2gdkigkuw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sweek.top/Article/details/gt2kqaampnj.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gt2puurplly.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gt2lxgudchm.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2zyeednax.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gt2zaooxmmq.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbzmxkho.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kycwegyx.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2tlbzpofa.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2tkprjgws.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gt2xiesmwah.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gt2fahvfhyh.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gt2jajtgprf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gt2slfvwvbl.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gt2axzyilqn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2bgwklogk.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2ttcgffha.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gt2cokmcslt.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gt2tgzdiwfc.html


<!-- 参考信息 -->