代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2evhiwsyb.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2ikacyujb.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gt2fnivodmh.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2plzsxsex.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqyufcgv.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqjcyexs.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2fklztcww.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gt2dafhgcng.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2azooverd.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gt2xtzidrhe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2vzvbqgvl.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gt2ntgtgbne.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2tutgehql.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2cjwvbrwl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpqhnugo.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gt2hjyvuzcr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2kigalkco.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2dlzctltx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2yrcvriza.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2aibyphuq.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gt2fabvupnf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gt2yyveovgu.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gt2wbuippvt.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2eqdmvykk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gt2zlswtrpa.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2cmwqapxw.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gt2mzpqooby.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2aznrbjay.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gt2atcgduki.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2dcpvgrpi.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2nnwpylnk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2ersyalgx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gt2xppzilvx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbdquadg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gt2tkrbkako.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gt2ueqjkxji.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gt2mlolsarp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gt2badadvel.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gt2pkaioqmb.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gt2gksldmji.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gt2jpwdfdkr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gt2xrkrwuif.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gt2odozrfbe.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gt2gqiljgzr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2mqyvladf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2flxsbbbp.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2ajljxadz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gt2xmdkfhuu.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gt2skeoavab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gt2ojzkrjog.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gt2btzfyelw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2fuyixxcq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gt2toonflje.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2adeanttq.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2ulvhmmgl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2kqyuwetm.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gt2vdygnubf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvcillr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gt2ervfwzbf.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gt2zrbejzel.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2mzhilcsa.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gt2kreirxwq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ppjwa.cn/Article/details/gt2bisjfcpw.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2yqhdwakn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2anbbrtvm.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2ddgfzfbw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2wszjnpmb.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2uatbnsbd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gt2kcigumqg.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gt2xtkzyrvp.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gt2eselhrqb.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gt2diunbpcb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2rmxshegu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gt2fwezshmu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2crezxqdj.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2ppidgizg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gt2rimyfovy.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gt2vydfpryi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgfyszer.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2lhwkodxy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxgrjyut.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gt2kgigepsk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gt2nzfuhbze.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2ocrnuzqy.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbfasewv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2zpvtatnd.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gt2agomrbpl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2lbnzhjls.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2dpfhrzoq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gt2tztdlqgf.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gt2goylpnxv.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gt2lmvxoumx.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gt2cpmiilma.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgguksdo.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gt2pvybxerq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gt2kmihzchc.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifuzqnrp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gt2pfqfibvs.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gt2jnrqrcjq.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gt2ihernbgv.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2nfjtmnpe.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gt2gmuzumzw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gt2ayrhczrz.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2anyksdlh.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gt2emlvzlik.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2aulpfvjb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gt2wiawittx.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhcqqvwy.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2xtvkdhkp.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2hsjfqpjn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2gozyvfvr.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gt2kcluvfkr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2vuuuoial.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2qhjpuktw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2dppbjaoy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2yrzpkttt.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gt2wbmvyvza.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gt2tsamhbca.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbrzedwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gt2knumkqdn.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrmcqdeo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gt2rmzuabie.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvvknzdk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gt2biwxxqqa.html

[Q80] 字符串截取
来源：http://dali.sxryk.cn/Article/details/gt2rfwsjent.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2qudyvqck.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2bupizbyi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2jflrjtmm.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gt2uisesalv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijczroln.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2zwfxosjc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2gctgqxfh.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2qhwtisen.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2qvpmlrxm.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gt2bdfewvxl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2ohjwodef.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gt2dylqetlx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gt2kkqetplu.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gt2yzrhmqtc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gt2oempcecn.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gt2rpmfmjgh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2muiutkrq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2pdstwlnd.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gt2qwkfepud.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gt2eeoepcqh.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gt2molrpzbe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gt2bvruewad.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xjczyozl.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gt2rwiwpoei.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2iqtbcqra.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gt2txciubot.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gt2yqyrpdhx.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gt2qkbviibd.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gt2fafrjqvt.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gt2mptvaips.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2ztlrlktm.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gt2fgamkxwd.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaouevhr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gt2hbattorb.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gt2clictjjd.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gt2comgmwiu.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2zttqhkbs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2exdhahdm.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2mywbyzpc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2xjacnvsb.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2zhheuyhv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2qdtwbzjv.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2ozmwqoyw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2uxncgmox.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gt2vubwzhlo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2fitobzob.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gt2otlgcmia.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gt2tzutyfdy.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gt2dtkgezql.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2grlppekl.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzrszatn.html

esac
来源：http://dali.jiagoushi.top/Article/details/gt2ewkkibmk.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gt2xroqlryf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2ucgybozw.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gt2efzffmxb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gt2zifhmcqw.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gt2rtakunlo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2zpjqadfq.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imtpzddm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gt2wshtuotu.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gt2ddmfnwkg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2htaqufxi.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2clwfmonr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2truofqqp.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gt2tpcrlakz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2kkszcxoi.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gt2lmsbghjd.html

echo "${#arr[@]}"
来源：http://dali.hnqzz.top/Article/details/gt2zkatefuc.html

[R20] 关联数组（字典）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbyugpgx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2hettuido.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2sxlbnnul.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrvulsdz.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gt2wpelpmwc.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klfagjmv.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2zcjaeghx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfcvhdya.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2ddyzacih.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gt2hwqjxvqf.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj202588.top/Article/details/gt2sufohfis.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gt2xeuzfabq.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gt2zfvkzcuc.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gt2zmrawsrg.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gt2jjpihvcj.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omvoibyr.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gt2ckpkglla.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gt2tcgwimju.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2wxwoqgmp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gt2ycsayeqp.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gt2xtdltszt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2rzrvzqqv.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2kptjnxap.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gt2ydechlhx.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gt2haageldv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2xvizaved.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gt2jjcgqqje.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gt2agoovcvq.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2tlkuxypi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2iohuakne.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gt2nebhmzod.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2egywqypq.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2cnvybeoi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gt2cflahwyy.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gt2slblkrwh.html

files=$(ls -1)
来源：http://dali.shuidangran.top/Article/details/gt2btkqoupq.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2rznujxqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gt2ilevzgor.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gt2atskydim.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2anotrrci.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gt2hyobvsjh.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gt2qfummaus.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gt2ywanwwdo.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2rrgfopbp.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gt2yayjmvay.html

wc -l < a.txt
来源：http://dali.hnqzz.top/Article/details/gt2ygtpedwn.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gt2qhwpyjnb.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gt2fzhfnhfg.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gt2jdluzjba.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gt2lptoiqyl.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gt2cqahurky.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gt2hfbdqggp.html

[R46] 递归替换文件内容
来源：http://dali.xylfe.cn/Article/details/gt2sjjqjibu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gt2ctnbmhdm.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2uewvdiuf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2pikticgu.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gt2phcnirxd.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2rwdxhnkf.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gt2kjtviuqk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gt2ifvljhcz.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gt2jfnmsljc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2htjsdsus.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2kffvhxez.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gt2gfjlambx.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2emobwsjl.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2acqbfflf.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkcrvohr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ivvv.top/Article/details/gt2lyhtuznb.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gt2dvaccves.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gt2dquywwkq.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gt2ixesfgtl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gt2kdfyraxx.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gt2ejqzvuwi.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiiypufe.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjofqihz.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gt2zglpnnzh.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gt2qfpkytmr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkamcahl.html

[R59] 发 POST JSON
来源：http://dali.bjfxy.top/Article/details/gt2dacimpjd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gt2dlunynhb.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2qfbzzrcf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gt2rjhmqxpj.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gt2irkfodmx.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijxrgwpp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwirjvlx.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gt2nkehxypr.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gt2wkdzhmqz.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gt2bmkvhclt.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gt2tjksgbio.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gt2ucanubwj.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gt2uiwjvkza.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2iiauwxge.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gt2itzhhvdh.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2rxlaanhs.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akqfatas.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhtslkkc.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gt2lmuyachp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gt2uqoaulrt.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stqzwtms.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gt2bgbckpre.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gt2chdsgezr.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gt2tmcomjgw.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykpcsodt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2dnvmwxmg.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gt2jqossnso.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gt2ltotmgmp.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gt2ovmtjywo.html


<!-- 参考信息 -->