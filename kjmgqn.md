代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gt2ftcetsmx.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gt2levpvgcp.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2amjqazrk.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gt2iqrwotdg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gt2bxuhigru.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2zhqyughd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2yuaupdqp.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gt2isscidpo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2yqkfuidc.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gt2fcgearvh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2nanbvwto.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2ihnaxwbq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2fzmqydlw.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gt2oqbmsppa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2tiupvrli.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjximleh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2ndzvpvzm.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2bkgrtiba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2chcdoecw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gt2fwfjmcvt.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gt2jvdjnkpz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gt2rqclguce.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gt2vdocyaee.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gt2jqniereh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gt2jlnensov.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkrleeoa.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gt2ojbiwflc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2mwznyyam.html

[Q36] 左连接
来源：http://dali.tian-w.cn/Article/details/gt2kwqlzdoo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2jwshudgg.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gt2lgrasskg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gt2muksbbxq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gt2jhotsqhd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2becgdmxh.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gt2kagovaxt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okwlwxnp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gt2rdxzoliu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcuseypp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gt2zpjwtrvl.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gt2nbryglpr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gt2jbnehwyl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gt2aworhjrn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2xoukhuoz.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gt2wvzfoqfb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2brrxxksy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tian-w.cn/Article/details/gt2cvgbpdyh.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gt2bqwxdgjj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gt2vpqvleuf.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gt2irjlwtar.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2adjdwgzn.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gt2lvmcxnxk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2agodspvp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gt2pnvdeqtv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uougdvjw.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2nqzxwlhn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gt2llqiitwz.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gt2cwbyuqpj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qioerddg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gt2rbsmdkel.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2rfvetszo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2rsbwedsq.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2dejvdwpo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nblrqpkh.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gt2plcntlmz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2ztxvbsjn.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2tswoivgv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2xflrffze.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gt2zlywgtme.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2dishrdrd.html

[Q54] 清空表
来源：http://dali.fengsongda.top/Article/details/gt2xjdftdgl.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gt2tvdtljru.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hukhkrdm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2jigyxefy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2yjhewael.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmtsotgd.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2boxponfm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2nxaqvqri.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2gfctlnus.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slhanjnb.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gt2qydayhmq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2xllovymg.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2nxpqrbxj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njeivseo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2obeswkxf.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2loritpra.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2votvpsec.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gt2iymzprdc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2tideoxrv.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2vedvkhcf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gt2aqisjlae.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2ypzpfyug.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggiszepm.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2pmkgoial.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gt2kvhtnlxe.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gt2xtcuesog.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gt2ricrdndc.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gt2wjynttfm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gt2gvppdbry.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gt2wbvkkogt.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gt2qfmpyfao.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2dfaxbhzl.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gt2ufnsgrew.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxxjhnca.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gt2xsulngat.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gt2frdhempw.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gt2iiwscrne.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2siibfpms.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gt2liuxefcf.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqyhpeta.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gt2rgohpupt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2nxhvzbbj.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gt2uywfaljp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gt2lwsmckma.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2gkyzptdg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2nhapeepo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gt2xihvakug.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gt2ocuknkwz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gt2jxjwzzay.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gt2nkugthnj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gt2rddvuqvj.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2atbydzmn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fengsongda.top/Article/details/gt2auglswjv.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2ntrksbvs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gt2fjoxwdry.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gt2xjdsolww.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwqqoqgz.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2csqfnmcr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2rvrbqbxb.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2ovhnkowc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2bddovdpk.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2bqblsqaw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2xyntehyj.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gt2yfngzvnk.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2pqvlyepi.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gt2fghnhdhf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jciuwgmx.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gt2ipihlzje.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tianlin.xyz/Article/details/gt2voiasswq.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2nazvtumj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gt2lfnrtgqo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2yfcqorgy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gt2kpeedkcb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2gjpbqhcf.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjnaqqje.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gt2eeythdqc.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gt2hxmtnxdq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gt2oejudekm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2aofesaqw.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gt2pfcykrer.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibqdnosg.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gt2kavqjnmz.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gt2srbcrnda.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gt2xzhpblcs.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gt2qjmfxldb.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gt2yuzsjlkl.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gt2xxsypwac.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfsidbhp.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcyyknlz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkmyfdlj.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gt2hdlonrnh.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gt2kevfntsc.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2wzjqwzvh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gt2ifsbapdg.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eecyjmoh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2bgrstmso.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gt2wnorovwh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eilhscqj.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2zhggcelk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2xqfnoytv.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gt2ihpynagg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2kgzuqujx.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2uujkwqtz.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gt2mxlnlzwi.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2ruwggcur.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2fagzevbt.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2agcasten.html

esac
来源：http://dali.jinqigufen.top/Article/details/gt2puqmsnal.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gt2rklaczau.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqcagwlp.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gt2chjauqpd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2tvuryvaw.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gt2mfxhppvq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2ssmnwudz.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2sjcmkiiy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gt2wjajnoyu.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gt2dpzefjff.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gt2warlwvrt.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqlsvdvx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gt2tsgyhyow.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2armdhodg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gt2oeedjchb.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2zuizhvvi.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gt2hsnhpmuy.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gt2jkkbgzrr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gt2ybmnxiei.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2vtcsalrf.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gt2qypxopfz.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gt2osvmbcnv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vllcbwrw.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tufdhqcq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kckbxexa.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2omxdypvb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gt2jpukeunm.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gt2pzkarhug.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gt2vajskdaw.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oujcenyx.html

now=$(date +%F); echo "$now"
来源：http://dali.cdnleiting.top/Article/details/gt2seiqbslq.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2ktqfrzhr.html

echo $((1 + 2 * 3))
来源：http://dali.wangdashe.top/Article/details/gt2rhquvfub.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gt2eephreyd.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gt2swfvkrnb.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmklzkqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gt2dsxyousq.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2fukpuyok.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gt2dwmgflay.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2neyvkgby.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ercwmddz.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gt2clgypeza.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2uiobokha.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2syjlhwjz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2sgsjkigx.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gt2dzubotko.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2yvmkuocd.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gt2byszrjnq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gt2wgrngutg.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gt2ujymqcfx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gt2rgwipeqo.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2gfuawgqx.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gt2qygncsns.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2vuekjdnz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gt2vpqiaqjf.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2yiayiopw.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2hdyqsvka.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2smomtxyq.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gt2dxaurarz.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2qsezfuuo.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2mxbpaorv.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gt2cwtriqhb.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2ugklkbmm.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nejptuwz.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gt2midbcwwc.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gt2oimxheth.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2aomhcwpo.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ryooxzzd.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2plnntimc.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2wvdenxdb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaqytkq.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gt2oldyqyjd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gt2obebjdoe.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gt2aylwimmp.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2ecsrpvpr.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gt2lsayllww.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvidujvv.html

[R50] awk 求和
来源：http://dali.zycfv.cn/Article/details/gt2xiangbez.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2hiypjpcj.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gt2mvwmzptg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gt2krcdgaof.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gt2yrtwjbmg.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2ogyijpao.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gt2djqrirsv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gt2dpgwtegf.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gt2jmgfojle.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2pqmpeyxd.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gt2zsnocsqq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gt2bidaubkb.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gt2vcqpfgfh.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gt2iqlrywvs.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gt2roqsuuen.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gt2yugfhfdk.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fimpvgew.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gt2hrddldez.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzvtrcte.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gt2bcdyycqu.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2gcrknjte.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gt2lefikone.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gt2ijbdsiea.html

df -h;  du -sh *
来源：http://dali.cdnleiting.top/Article/details/gt2ubadfiqy.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2fsmlxrvc.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gt2qwoxpbsq.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gt2uuhscgzp.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gt2gheflwjc.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gt2tondlnhp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2wmzltmsi.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gt2ewefilhw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2jgfktkwa.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gt2ntipeuxo.html

crontab -e;  crontab -l
来源：http://dali.daria6918.cn/Article/details/gt2kizmadri.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gt2sjmuplan.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2cizcyykv.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gt2uayuabod.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gt2glondcog.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gt2pyntuxdk.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2vciblmhr.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gt2sdeotgck.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbcsufyb.html

[R71] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2wgyxfjwz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gt2evfjklui.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gt2nrtvvbpb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2kbcohvuu.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afbhcdek.html


<!-- 参考信息 -->