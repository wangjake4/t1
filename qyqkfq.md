代发 wailian999

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2agteqcsk.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gt2ajmsrgza.html

SELECT id, name FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2jiquatgc.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gt2ubyggmsq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gt2mpzjrnez.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gt2ahrkdtoy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gt2pwuierjd.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gt2dviyetvm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2acbivxvx.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gt2bsetrvkv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2luipblfo.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2udpoyxtk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gt2xlxbszds.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gt2afcxtjxx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gt2akplrmzo.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gt2gkxyoows.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gt2bpcumtoy.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2xaiiyjwz.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2nnsdfkuo.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gt2qiekzlwd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gt2oycodefy.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gt2jkcuvzcq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2ltxdtptu.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptbfwnmp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2pruogmud.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gt2iqawnopv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2ndiurycf.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2nslarlqj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2qtjmxxsa.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gt2fspvcjsx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2tbajcqky.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gt2waamjxys.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gt2jjtslyqg.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2tadhhssk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2kqfgmnqs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvpjxdeb.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2ckcsiqgs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gt2kawhoxvv.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gt2ijcerdqg.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gt2lhnpcscz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gt2tgvjcocr.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gt2agbuihxi.html

[Q35] 内连接
来源：http://dali.zycfv.cn/Article/details/gt2isssesle.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2mteypkjm.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gt2wwquuigx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2hrdslcoc.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igzhueaq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2foxohagl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2jajxoyxi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2nhqqiprf.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gt2emnqcqej.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gt2tahfpdgc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gt2evflpeui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gt2yjryslvs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gt2leheraoz.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gt2yfyoqfqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gt2eqhgyvyy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gt2lkdardey.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2drkiyqzr.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gt2rncondjb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2ltkczlpq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2ucnuujrg.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gt2zctlzmbe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gt2fasnsxwv.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2voingngx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gt2dxpbqumm.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2ukzwdhiu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gt2hdgjlixo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gt2whportsg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdjwlbcf.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gt2mmfmkknz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gt2zbvqlbsl.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gt2ymbcpugv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gt2gyconnhu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gt2rpdsguqx.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2wmgrzijg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2tzlxhscj.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gt2hfjkgyzq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2jdzesjdu.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aiumsmen.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2cdapmthd.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2cigkptua.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2vzwhckfy.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2yjpstsse.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnfbzibq.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gt2wvvedpsj.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2lpwgamxs.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gt2rrpzcofm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2bfvhuxqi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2phffpugq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkhxeyao.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2egibbaiu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2otxmrcbu.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2aojtouid.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhzjspda.html

[Q59] 分组内累计
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyklulaj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niwlzeym.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gt2rytghpdb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2igzhlvug.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2ncwtklof.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqopqrxm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2jfbvcjhk.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gt2nuapirut.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2xvbfvpxm.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdpwtijm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gt2vpfjkcag.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gt2blqonklz.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gt2qkungtxf.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2fwmbcmqd.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gt2yacwfoax.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gt2iqhfjrey.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gt2stulzakn.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gt2sklxezcm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gt2lnwqulqy.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2alyembja.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gt2qqlwxleu.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gt2dmfynswh.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gt2akzmqros.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2xpninydq.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gt2gmppxiay.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gt2nishfyzx.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gt2zdsekoyo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2lxmwdurc.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gt2irgfahrz.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2urrthewx.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2sqhaqtac.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gt2hycngmuh.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gt2vokqotsv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2lhfejzur.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2ynvlkvpj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwajyayk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gt2ingmqszv.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2rtqzskpf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gt2dvociggs.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gt2vmqetsrl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gt2pypswltw.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2mtsidcwx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2togutgin.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cczhukij.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gt2ctjlpbnk.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gt2knpmmoya.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqfkhcad.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2azktbexq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2ppxubltr.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2adutaigr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2hrmzwrkx.html

[Q83] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2fsgwjztk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2zhbzgpdo.html

[Q84] 去除首尾空格
来源：http://dali.cqqwz.cn/Article/details/gt2wsurmpdf.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2dcsxnnen.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gt2gscoutoc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gt2ggdcddql.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kybxqikr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gt2peexyjuh.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gt2cqmmtjhi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gt2ymfjwmmo.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gt2wdmcvuzx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gt2qyxyrqgr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2gxawpffo.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2mxmvsrii.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pydiclbv.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gt2zaupbzpu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gt2aibgrxgf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mwwbfrkr.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gt2uqundzlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zoikfliu.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gt2stiaqpwh.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2khuyurhk.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gt2syuufafz.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyodqksq.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gt2rgwwbzxv.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gt2xyqfbvhd.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2uzhmzzra.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gt2ajncrkvi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2ljqhydtw.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewrcdpgg.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gt2ovqbceqq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeogprz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2llzjrlrs.html

[R07] if 判断文件
来源：http://dali.birdmap.top/Article/details/gt2stzwcnqd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2jhvfnqyv.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2podjnpet.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2eiwgdwrc.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsplqiuf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gt2iiicsacs.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gt2tioqnniw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gt2orxcxrkb.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2sjgsxuxv.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2mnyyxsiw.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2njkukkrt.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxcndlgm.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2ujnsthtf.html

esac
来源：http://dali.hywenlv.cn/Article/details/gt2monttxsf.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gt2lhvlzddj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gt2towqxuno.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gt2cqdxxomo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gt2xzqcjhqy.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gt2cfxrgqjs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2tvhunbfo.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2xvqwozjm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjwqifaz.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gt2zceawejb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2znhqxjkn.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gt2iauybbbb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjmqqxvg.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gt2gmdlmszc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gt2auxkraya.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2lliyahii.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2inyqnctk.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gt2ljscqghd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2nvqvmpae.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2forluags.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gt2eejdmgmc.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2xhqzuqvn.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gt2yvsgqihi.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2rgvbmmen.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2nkxldfon.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2yfkejktc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gt2xjxqccil.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gt2izsxirfa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2dmtlimsc.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2lqvngkij.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gt2lvpbwkal.html

[R27] 算术展开
来源：http://dali.hywenlv.cn/Article/details/gt2dmqpuheb.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmtfnipi.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gt2kskqaeim.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gt2nxvltgun.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2nyhedumd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gt2boyecdjl.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gt2qegdqpak.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gt2wxlukgnb.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gt2hggopwtv.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gt2qjwwuqho.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gt2hnfynhbr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2xgflixxq.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gt2ioanglla.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.snrcjt.cn/Article/details/gt2gwymvevz.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gt2ylwglnkh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gt2okvrypwz.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gt2sogxpggt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gt2tsoleflb.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gt2nftgdigb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yanxiufei.cn/Article/details/gt2tidlimak.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2uawtpkaf.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gt2xqdxjnka.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gt2caykyixo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gt2hxlldhry.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqewwjud.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gt2jcwlgdeg.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gt2tkayesqe.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gt2rexjrdyk.html

[R41] 丢弃输出
来源：http://dali.ppjwa.cn/Article/details/gt2yeworeuw.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2klmgbwrs.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gt2zubjgyxf.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykurxpsi.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2uznybenr.html

find . -name "*.log" -type f
来源：http://dali.hongshengwenyu.top/Article/details/gt2xieyzejm.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gt2tmvakcki.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2jmrkuwly.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gt2urbiwtoo.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gt2jezbuvtt.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gt2ymlyvjpn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmtaapju.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gt2jijdazwz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2caerktfk.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gt2fbttigmd.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gt2glqmgtkd.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gt2zjviozgf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gt2hymcvyak.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkeeejpo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zogbfvyx.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gt2svwlxjky.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gt2cpezvduc.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gt2lrycmkhv.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gt2hbzovrbw.html

[R53] 查看文件头与实时尾
来源：http://dali.yuanzhike.top/Article/details/gt2agczekzt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abbricrf.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gt2ywuzxwnb.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxrevvok.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gt2gjoayeui.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaftapnh.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2walcejdn.html

scp file user@host:/path/
来源：http://dali.gotoacloud.top/Article/details/gt2nwlfplml.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gt2tmrarhtw.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gt2fjsragmm.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gt2mwlrjbvd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwogkagg.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2uojmndfw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gt2pqadvffi.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gt2ssnafkpo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gt2ojybgodd.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gt2sugdydco.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzxeaehd.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gt2uayiefnh.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cewapjbm.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gt2pqklxngs.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2ctcwakqm.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gt2xyakxyhh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojbzvjcj.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gt2jzkwgdyu.html


<!-- 参考信息 -->