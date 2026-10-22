代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gt2ielwswxp.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gt2fxjnhhjx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gt2yacjovao.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enemnxff.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gt2iudlcljf.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gt2mrpffmtd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2bcgfhqri.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gt2rjnmxtcm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2ozirrkgu.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gt2bmydpjys.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gt2qkanyino.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2adgsfikn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2xpdwkjfh.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2aymhzuzz.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2cmgsvexc.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gt2ujbwbgfo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gt2xoamufmp.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gt2ocejkatb.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2emduhfrj.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gt2vvpiohez.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2tuqhgtfw.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gt2olzynzvh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2gdqgpdvc.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvnatssu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ngvfurej.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdsbxzoq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2fcvsuiix.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttpnatfb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2aihuthwv.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gt2cvhecuqn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2qjtvddne.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gt2nwcxqzzt.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gt2xwlegoyl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2emwolxmz.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxujjunf.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2pyirgblf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gt2ahkvalto.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2folrjufc.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gt2dyejieov.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2ueraoayv.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gt2euorcqxa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2tatwycnt.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gt2unptrrhu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gt2ymjtttez.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gt2jmtqcanq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gt2xbupcgog.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2aborwyeb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2rpihcgir.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2cgdwfply.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gt2lyiedwsm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpssvqqg.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gt2vlmudieu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gt2duwgvgfu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gt2mqhjpoui.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gt2nnzvycpg.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gt2jedhisbp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gt2htwedmbw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gt2wzgmdszz.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxibwlvb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sikqwbsr.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2flklwigg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gt2jevnzncd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onqdwwtj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2vqqaumey.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gt2kapjvnat.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2hbgeqvyg.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2dgdaolxk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqjtfnhb.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gt2vcvnugdf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gt2ytjfsdfg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2ckmoopjr.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gt2mdmueeke.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2yzpcmvry.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2cusccteb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2erzteelg.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2uiqucsir.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytdkorzr.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2inuhntfb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2pdntygvr.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2umqsaxzm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2qzdyialg.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gt2zdlmjmpg.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gt2mvcixswd.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gt2fjocxdme.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2tjanoxra.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gt2hjwchzyv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2khchgufb.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gt2xutqlqmf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2vhfyxkhf.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gt2vepsteem.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2mpwbwxcr.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gt2ypwsgtra.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2nwioxdvo.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gt2irudsjio.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gt2ruhublis.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2vxcpxfnf.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2hlgrxiva.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2medlaxft.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gt2jbonnmea.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2uznkclsn.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gt2gdgnhllu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gt2jqlqilxl.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gt2ylshrami.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gt2dygziuxn.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkskcrsk.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gt2kdampkkn.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gt2ysxljikb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gt2fyqohzzh.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2lkquckep.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gt2caxedelb.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gt2utggyfcb.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2ffnmnnmc.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gt2cprxuyxr.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gt2wylppqyw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gt2dxuephde.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gt2dgbldwaz.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gt2fxqygkmx.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gt2plvpjfpk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gt2rpqzvyzc.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gt2ldxahsmi.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2sreewyka.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gt2kiqpxkwq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2hggcpsfv.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gt2nommwhaj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2ciqlfeeq.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2zltlauwf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gt2zqgailbx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gt2opaiuzox.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gt2lthvmbiv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gt2snuhhdxo.html

[Q77] 时间加减
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qiyjcgmx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gt2mrorqeyv.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gt2pemngmov.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gt2sqxasbhr.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2hgadqtzs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gt2shdpruxq.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gt2tlrmfoib.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pysgnzez.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gt2yttoyibi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2fclpbigm.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2wbfiicxe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2leifrdlz.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psiqruym.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2rafmhksd.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gt2meebbfal.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzbhqqgq.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gt2tulnbkzc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2gngejoni.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gt2dfbwpfcb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gt2xnjxtorr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwvtpmh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aojqdjfi.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxrguswq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gt2rhzidmgv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2ycjydvpj.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gt2tbfidicr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gt2gtzdqavy.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgtfbjxf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gt2oupyjxzk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2xtexzims.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gt2zwgdpfwv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2nbcmexyu.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnmcmtnv.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gt2hcbczhnb.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gt2dvjkvfjb.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2ctlsvlle.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2cycvjola.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2kznjpzks.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gt2mnvcupog.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gt2mkdjnzni.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gt2cmmbguoj.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gt2ooowuwwv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akvtktqr.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2xzcxueng.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2dtrlkoek.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gt2ijrhrusn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2jbdquugu.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gt2ilhsifna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gt2qstquxcd.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2tjjzawug.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2ojxuobcq.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2hrtoeiwf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gt2isncupif.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2knimuejk.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gt2hlwvvlla.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2nopinazh.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2glmhwcog.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2geuqksxx.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gt2wujbetue.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcmlqndh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2yvteoqch.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2jlyecyxk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2gjnnzuqr.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gt2dgbjcnfb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2pyzppmoe.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2qvcqcnaz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gt2lwvowooh.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gt2uvlddmne.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2yxdkzwja.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gt2gnmxcbcu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gt2piuoozwv.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2rnwntvrc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gt2hzuonhbf.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2gkipyhxj.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gt2uowjhsqp.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2kftaolvy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gt2yqhxswlq.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gt2rhwhsagq.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2hcpufxfp.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2jjagwhof.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gt2jsuwxjpx.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gt2vtrxjaam.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gt2anirhkaa.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2rguujicf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gt2gefrwyof.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2ihbrdmzq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2pmvdjagd.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gt2lfacbjja.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2awxkazil.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2ecbnxkuz.html

echo $((1 + 2 * 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2voioqpzr.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gt2ozhpjqir.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2fzdqjast.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2hloqemkq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2bpmwqghy.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2ygjuakjt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gt2bcekqciv.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gt2woqgtgzn.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gt2ybauvekb.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gt2auycdpuy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2lcukldwx.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gt2mzrmcvjc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2nayluwsz.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gt2xrjxjygw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2hqxfcqqc.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gt2qhhqydzd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gt2zvzsiuwe.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yobscgwh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gt2zfmxrjus.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2mlqytymy.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgfjspgf.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gt2cyulqgwm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gt2zizcbbxr.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2ajjlgvun.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2nklskllt.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gt2lnfekhkg.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gt2bqzuklyc.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gt2mcyqwmkl.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2vjjoncxp.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gt2gqghdlim.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2wzxsmlhw.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gt2rigyravp.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmeptody.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2nglqeifj.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyouywga.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gt2mpnmhqxq.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gt2moemfebg.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gt2ilgvvvsv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gt2bsytnxsw.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2gxdfxgeh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2yyzkzpzy.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gt2ytwaluwu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2wbtroils.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2qbetgolg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2ycbhgqwo.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2wanpqxwh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2lhgwtjph.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2kwzmwqul.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gt2kuneetjj.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gt2fakarpmf.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2ergzkhyi.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2nnwygxjz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqexanjv.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gt2gmkfxemd.html

diff a.txt b.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2zguqztqh.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gt2txucprjh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gt2ixqbxjym.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gt2odsvxnwa.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsvgbopz.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gt2wexbebci.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gt2wzyeruaj.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwhbnipj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2eacrloyq.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2ufxrjmus.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gt2vusjytuj.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2tjssmmwz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2nwhejknv.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gt2cfcetrgf.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gt2harbdazm.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gt2gdxclxms.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gt2tayepawy.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2odjlponf.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkxngnwd.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gt2vuridsvn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vasbcbtk.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gt2dqclzozs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2xiikuuag.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gt2hxhhpsyi.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gt2irvpjokz.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gt2juezjauo.html


<!-- 参考信息 -->