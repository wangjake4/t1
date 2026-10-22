代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pziszpbr.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gt2kqpbbitg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gt2eccvlany.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gt2qqhzmsol.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gt2fbzavauv.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gt2jwcjvhmu.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2mfybcasg.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2zlwkmppr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gt2wgeqivjg.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gt2esluvard.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2mysbvrxo.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gt2xewbowua.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzvdrsnl.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gt2edbiwcim.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2zcusyxhx.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2rfmatrun.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2qetnlkhp.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gt2woflpgpz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcfkmkot.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2zpzcgucs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gt2cxbnbabi.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2cvcgyqpg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2hfpgqmzm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxqdajrk.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gt2zwoqveww.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gt2ioxfpxxv.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gt2nttxiqty.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gt2lusqazsw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2nvkwuaul.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2pqkkxrkw.html

[Q35] 内连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgxyrywc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2fqforjgl.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2bryhjifl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2pnvjjsnj.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2cdvlgsaj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gt2zsocmaja.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btirwkxr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lekqklmq.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gt2qeogqfxu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gt2izbcluox.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gt2qrkhjghw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgufenzy.top/Article/details/gt2mcacsbdq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2kutjeusg.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gt2lpzjgdcf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gt2ihxsgzue.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gt2wsjiuitw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmedlsvo.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gt2bsgottxq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gt2mzcklpcn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2ykuhnmlj.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azvilwwg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2slqhktkj.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gt2geycsgox.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gt2kketqont.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gt2ftthyjik.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2ipaadkej.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gt2seyhxyhp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2qnmxcmjm.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gt2aylbxhuz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gt2qptlbobk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjzlman.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gt2mtatibpi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2geqosvri.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gt2fgfbdzik.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2dnjlbsfv.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2lryzlvoq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2wfctvgqg.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gt2owogoopk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2dcyjglpe.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzhvrwdg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2ryqncfht.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dszutuml.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2udzmifcx.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2tllcaoun.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gt2fmdffnfs.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2leqhmgjw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2ooyxhxpq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2aflnofwf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2vtmxigsj.html

[Q57] 行号
来源：http://dali.jqgufenzy.top/Article/details/gt2fchelwwe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2keylgqjw.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gt2hnhmrfss.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylvnxxab.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gt2lpwszkkx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2gkfvrrpy.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwqudqqd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gt2dxpdgisc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2ctdihuqm.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxcykifb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwubmkiz.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gt2hhorffhl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueubcbxv.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gt2yprsfkwn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2gqwfpyyh.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcglceio.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxbupwfv.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gt2upmkhkai.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gt2vrhaefew.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gt2yyklnxyf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gt2lhokxshq.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gt2fvlqwpey.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gt2fgnmlnin.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gt2vytjyafa.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gt2ytxhttuk.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2vcbvozqh.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gt2qqfqiopw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gt2kbkndwpf.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gt2jjyhmoal.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gt2xqxtoqmp.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gt2lqkqlcem.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbmsprdw.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2zliblwjh.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2etmhrnym.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gt2mrljking.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tprpqptw.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2juooxflo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilknkcmr.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2fujtxswt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrvkdkvc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2fpudjgab.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gt2eqfxxoah.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2hkmqxaeg.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gt2jgohnzbp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gt2auwmblmx.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnddmwle.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2xiqcyorx.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2seobaaxx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gt2kebullrd.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqtzjllf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2hnqdjbpc.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2qljafofo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2rcmsxvoj.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gt2egubyffi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2sejlvlea.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2fofeucpt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brnozwnm.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gt2hnreztum.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2isjzgasv.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2kupluuqf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gt2rqxcibnd.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gt2ttphwdtv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gt2wrtzzxax.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gt2mpheabrc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gt2loupeint.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gt2kmjihytb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqlbrbzn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gt2cqhmcrif.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahyobrbc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gt2kbmxbgts.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgxcjfhb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gt2bljewdvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlndkwq.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2ndyxammg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2czopocwu.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gt2ulnnbafe.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gt2rckgjzfp.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gt2fmwmyljm.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gt2fspuvkus.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imnojnzr.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppmmjwft.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gt2mwayfdnc.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2pttwzvqm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gt2ilzbbhbd.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2zihmboiz.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gt2dokegxya.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gt2mfthpctt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2agfxjuxu.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gt2kanjvqgf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2txrzxeup.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gt2yheuzueb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzrdzdg.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptnmqawt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gt2oltoqdis.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gt2jitkydmf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2gdtvowmd.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2nalalgmg.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gt2blbnvbto.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gt2rlekodkp.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddzolaih.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gt2ctzciphl.html

esac
来源：http://dali.iojbl.cn/Article/details/gt2ocfxjovc.html

[R12] for 遍历文件
来源：http://dali.jlsjyb.cn/Article/details/gt2jaqplbkh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbxekjj.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2edrdhbim.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2nimbkvlv.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2wjbtzemb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gt2pzeqcrec.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2xsmvvndq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gt2aawpzedk.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gt2qbyjkdnm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2unyexvji.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gt2zjjdaknj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2bfvjjsfe.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2oztmvuuj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2dxyrpvxd.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2dgoacwgn.html

echo "${#arr[@]}"
来源：http://dali.cheryme.top/Article/details/gt2wwlwftkv.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gt2mryanobv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2lifdfzjz.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2diluxfap.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gt2gncwaduf.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gt2vayqwvma.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gt2irpckgrc.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2byczbrvv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gt2slsnybsv.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnxbyoda.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gt2whhhfjiq.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gt2vefkgfge.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2pkdytvgj.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gt2ebrvniti.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gt2jqujysqf.html

[R27] 算术展开
来源：http://dali.jinqigfzy.top/Article/details/gt2vmmwqwux.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2hphryvhb.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2brjdmgfz.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gt2xxxmcrwg.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2jtaebodc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gt2dwtkmzom.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccrjsfur.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gt2mhcxtckh.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2losmgtkw.html

f() { local x=1; echo "$x"; }
来源：http://dali.daxiang520.top/Article/details/gt2jsavhveq.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2qevywzzw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sgxqhrxk.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gt2cbnsdnkp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggdtbkqh.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gt2ceksfwae.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gt2otvkdigj.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2mhcmjakm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2aiomsxoe.html

[R36] 并发执行多个任务
来源：http://dali.nanxinkj.top/Article/details/gt2hcataamw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gt2jjmwnatz.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gt2pamgqkmu.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erzhylyw.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gt2hpyujhmj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gt2hhdotkkl.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gt2rqgxtskh.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2wivodmyc.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2damngwrw.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gt2lqdskqpo.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlhjcvny.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2wqewgnfh.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gt2lgyswmjm.html

wc -l < a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2wshmkupy.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gt2ldcgmxcg.html

find . -name "*.log" -type f
来源：http://dali.316326.xyz/Article/details/gt2gztnapho.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gt2hotqjids.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnczarwb.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owfyyqjg.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2fajhgnls.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gt2xbkejjuy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2ouuulndb.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gt2krhgkpeo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ukykvplu.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gt2btvpiimr.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2wvapxyei.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gt2oaqwfffa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.c1oappe.top/Article/details/gt2dbbxjwpb.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvsdzpau.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2mdtopzfl.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gt2qgqimdlq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gt2wzcnizpd.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gt2onyuclkf.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2dxddmtjb.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gt2cihfvlgn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gt2oefrjtgh.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gt2wnmclobn.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gt2inufrfzm.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gt2xuyqcicn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmelarbc.html

[R56] 远程拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2xifusxuh.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gt2jdzdpvad.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2gfodvyak.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocntkpcq.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gt2rdlfglel.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gt2acyhishq.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2bjrqpxnn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jehalovf.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2jdhpuows.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gt2gcepcnws.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gt2vdpjydjm.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gt2flmzsrgg.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2tsbwncdz.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gt2xqlzsaty.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pnsuuavv.html

free -h;  ps aux | grep nginx
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmsdspal.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gt2rxszqlgw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2cznmapja.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gt2dlhbjxbk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gt2rshgmhuv.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gt2jpzqdfmo.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gt2pacoznlz.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gt2vwjgrmty.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gt2elqyqphl.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2wjvzview.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2nevqisxg.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gt2yktueqzr.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2iuzmooja.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gt2ctapqfdt.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btguprwb.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slbezhnj.html


<!-- 参考信息 -->