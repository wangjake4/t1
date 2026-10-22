代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2aokjqiwu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gt2foekuusd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gt2dzcpeiwj.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gt2sxxnnvrz.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2zhfuyhrb.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gt2imyagjom.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2uhjyawsk.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gt2swkghwzp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2kxgnbfly.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2nzqmaoci.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gt2dtopnjrl.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gt2htpamvwk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gt2xqzbbuvz.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gt2psblvykz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2jxbpcbmn.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgiknkgx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2xctagvfw.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gt2tfseyvof.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gt2yrijlnqm.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gt2fvmxdpuk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2ywdoitpf.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2wqbihvru.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gt2avixjovm.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gt2fbbpobta.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2bqjtbzsi.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gt2cwimbtqf.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2tbzxbjrx.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gt2wmlxxbtj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2bwtqeyvb.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gt2epjafyem.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2lfxyfped.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2xxaptiqh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2hfyjlwex.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gt2mioeliws.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2vimwbmyo.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2ktibioyb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2jexfmfdi.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2oqrztmwv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2oyqpxfbo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gt2rlwrpzdk.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2ffypbsqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gt2txqlflud.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlvlrban.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gt2hjrgvkbt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gt2gjeycwrk.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2ewqwywti.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gt2vhjwrztu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujtjtumk.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2btsrrish.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2hueikbdr.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2tfidpyws.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gt2goktcfij.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gt2hfmtaxaa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2gxftylvc.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gt2bsobrxmq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gt2awdrgexh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gt2xgoygjqd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gt2caaksxsi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgldttlf.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gt2quordwbj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gt2ulduukhe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gt2miqeqsgj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gt2ffruzphr.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gt2zjivpfks.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gt2rboofkdo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2vjywljvp.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gt2qvbsvcnp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gt2twanwsqr.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2jdoelkdw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gt2kcffmyjb.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gt2audmnpan.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2fyyxiygg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gt2xcuxwwuq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2kplwyjkg.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gt2kowtfsqt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gt2lffovacl.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlkmdcty.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2ouxqhesv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gt2tkgjnzkf.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gt2tpyfbsck.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gt2xbqpmzxj.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gt2rqpstvrd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2fipmtrwt.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gt2vgktspqm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzzamctj.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gt2uqckrkfd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2swvjnwjg.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gt2ehddwvxz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykfctial.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gt2rxabeiru.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2vcyfzvog.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jclpgydm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2ybieprls.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gt2lkieriqa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqdqklrv.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gt2tcemihyc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2huvxctgn.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gt2oadakfrl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2dgeqikzp.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gt2kpnpbjqp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2krzierjm.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcldxsxc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gt2lhpdlbca.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2mrseblhh.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gt2ujebrein.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxtwxxkw.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gt2wcuonwsw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2ncktdvpx.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hunrjrsh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfkxvkax.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gt2axaehxnh.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwavbumi.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gt2pknxspbp.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gt2efuinmtu.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gt2wniraffb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gt2rbqdkabg.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2djqflscn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2cbxjqspr.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gt2wvubuqat.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gt2yhqjvkrb.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2sajkucoz.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gt2gskgpstq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gt2huomzxad.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2ilhvvzwd.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2qpiqvqvo.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gt2hlwyqsqq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gt2rxbmenev.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2ptsadodb.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2vgncbchb.html

[Q73] 查看表状态
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgbuoozr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gt2petgqmfc.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2etfklmdr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gt2uyvkhwcg.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2uyohwmoj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rryeywza.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2onvcilux.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gt2bmaecraz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gt2dhgmhnxp.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gt2kphmctza.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gt2shetganv.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2rldobqkw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gt2yjvuaark.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxqzbav.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gt2itlbvdsl.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gt2zwuvtqkj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2nkwzfehd.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2mvqutgeb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2bivgjlzs.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gt2soufolpn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2bqsyhrev.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2jlxkfdci.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2expblpmb.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2dvnahffv.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2poqcjrjt.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2vmrsquck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gt2kvicaeiw.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2wpcbygsl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2ludzwigv.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gt2dxfebqtf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gt2gqpbrylo.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gt2ygyvdyxp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gt2ojdtgvlx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2crsciziv.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2tiepunbe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2mhwkyndn.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gt2fdijggpi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nljxbwwu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfpypiyf.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2zalinpox.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2spbpskjc.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkhbpfdb.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2cpluxnml.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gt2wainaiva.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2frnsxixf.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gt2jwdjilbr.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2golwdzjn.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gt2nyarvrja.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2evaqbugx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gt2hyhktgcb.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2jnvdmaom.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gt2jhzerlwm.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2vdtjugse.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2tblpksaj.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gt2qarnfsaf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2vlbtkvvt.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gt2rzuaroxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gt2kaxalhdr.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2yqscbhlw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2vtfauqjt.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2qoipesdd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2lkkjbvvf.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gt2ogdjyvhs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnarydl.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2jjvdjdme.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gt2waxrctjn.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2bjwsvtpx.html

esac
来源：http://dali.cheryme.top/Article/details/gt2eijwasrf.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2zozxerqk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gt2uhbqbltd.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2dlbhqbqs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2hopwrlil.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gt2ovfyfktf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2oolgcrxv.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2zcquuoan.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2dienlkmi.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gt2uvbajygr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gt2sqgqjxcs.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gt2tyzoqnuv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2hzzfmsjg.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gt2qgrzhgtw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2bciskumb.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2yntkkvdb.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gt2cgsuceiw.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gt2gsunifrq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zdqjudy.top/Article/details/gt2wqttygrk.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2qclooxty.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2znufbrgk.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gt2mjrpyvyd.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2ezqsxmzo.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2wrbsyafc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gt2tozpuvmj.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndvimixo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2pvxkxcya.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2pibhezou.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gt2bzxvhekg.html

[R26] 命令替换
来源：http://dali.sufxvd.cn/Article/details/gt2xexkhdrj.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyuintid.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gt2jksmxguy.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gt2tdstgehv.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gt2ashsvvsw.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmmgtktk.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2bvoetjqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvpfzczj.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gt2xjjjrvly.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oclisrjc.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gt2xehcmntg.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2ccmqfacs.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gt2jcsmtyax.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2khrtprce.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qysdnbfp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gt2wdmqgvwc.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2xgwgnkym.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gt2sztaonrj.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gt2lfjweuhv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gt2zsauxroz.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gt2fzxhvtzf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gt2ehbrrqaa.html

[R37] 把输出赋给变量
来源：http://dali.jinqigufen.top/Article/details/gt2xtlaapfk.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2apuvrsvg.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gt2hnedcjfu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gt2zsfprqlc.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gt2kvfnwzti.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gt2afwpvnos.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gt2rpqajayl.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gt2erjobluk.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvhekbdx.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2pxzdicex.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gt2vrjadyyg.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2hqvkiflg.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gt2kdtdeuas.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gt2hxytkyno.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gt2qwhumtpd.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gt2pblubpps.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gt2oaohjkey.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gt2obpjstaf.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gt2rxrsrngd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gt2igxnpltw.html

[R47] sed 单行替换
来源：http://dali.xylfe.cn/Article/details/gt2nlfyxuqq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2dhhysecq.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2xwjqvtba.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2vcwxoakh.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gt2oyedrdzp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gt2pdameluh.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkqkaqpg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2kiofaubx.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2simmoftu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gt2iwejljcv.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gt2wcwzjwbu.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2ikhphxvd.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gt2folaxdte.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gt2hqulgmdo.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2vwyxnejm.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iighkpvo.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gt2wpfareyk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gt2ovwvkjfw.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ferqufkm.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gt2hxehvvob.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2yqwvhxku.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gt2zwirelxj.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2azmqdipv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gt2auqmopbd.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2asekzlcb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gt2obzrngna.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2ujlwqsqb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2ycdzkjbo.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gt2okmrrzoh.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gt2qbnynfbb.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gt2gdhfzqlp.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gt2pntvpoqs.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gt2ssbmzirk.html


<!-- 参考信息 -->