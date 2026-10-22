代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gt2gagplhxz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2wdyoiefr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiikdjwj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gt2zuwrasej.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gt2vttaljdk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gt2aynkeawt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gt2gbznizin.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2aznoakts.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxurfkiu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gt2fpwrlgas.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gt2iaqopamx.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gt2gjveeqfk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnighdml.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2rgkyidzg.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gt2hkefkbve.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2bqenfowr.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gt2lfjkazmq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gt2cpfugtnq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2xbbysmcj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gt2peoladqc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2xsbmuwuf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgznptty.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gt2iwdcuwgw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gt2eouzumzh.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2dggydqnk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gt2rgjrkpvo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2edlvpgty.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csaeypme.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gt2uqjkrngg.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gt2soalmdya.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gt2pvquyoje.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gt2bfngdaxr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2fxewlrwe.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gt2dycfyzts.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2csqnguye.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2vtjxzrlu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2aqwalirs.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gt2dpoxljaf.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmotnsjl.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuykjlik.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gt2ozqyjjsv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqyhxwi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2vhqeeyea.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2sglyvtsq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2vxvpkolg.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2michswis.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2yziljbnd.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gt2ewsyrzgo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2fbjjsysv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gt2rgfwoavk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gt2chqhqqji.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2dvmjfrjd.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gt2qqhpnyyb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2jifarsvr.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2ihynclpb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2bercmtke.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gt2jekojmsz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlqsudpp.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gt2agjknkbt.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gt2gsexvrkm.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gt2uuhvwbeg.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2vkdlblmb.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gt2bavnbuwu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gt2yqthnyyi.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2kxdmmjah.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gt2jejidmco.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gt2lompoopc.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2rlgcqqzf.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqwoykuu.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gt2pffpdevd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2tfrrvrlx.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdueifxy.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cekiqoms.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gt2rnjkbtsz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2fyanfokv.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gt2joexxsrw.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gt2drpgpoci.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gt2puwozpes.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2akkivjtv.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gt2omnppysu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2ybpfqpjd.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2qwwamvsd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2zfnipgsp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gt2ssxummep.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gt2fgifzzxi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gt2hcuojzzx.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gt2ysiqbfcc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gt2tnvbipob.html

[Q78] 当前时间
来源：http://dali.guannengcc.top/Article/details/gt2nyutaelx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gt2zfrpiqtk.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2cfsjwswy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gt2kybqmanq.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gt2vrfwshny.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2zpmsqwvq.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2pwpopcdn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2flqxgnmq.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2yglhwutx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2tlibfgwf.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2kjyeexyx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2rnnacwva.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gt2japavmjp.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2jszookpn.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gt2uallqpyc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2lsvtpkie.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gt2crabovoo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gt2svbaxnsb.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2ujmbdavk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gt2yomvcruf.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gt2lukyymxq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gt2utqsynjf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2laagxwms.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gt2ubhnrmfy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2mbsxoxqo.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gt2tntobmmk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gt2omnczgac.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qqtirbpp.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gt2afnndnqn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vpbtlxzb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ciocdykf.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msmnwrdr.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gt2ausyhspy.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gt2bbbasiiq.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2gkbduezr.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpnbolao.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gt2bvcxqaip.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2otoucllp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gt2qzrabhjx.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2fuigikqq.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gt2xzwxvzqb.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gt2gwcxoxor.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2cxpbexkx.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtfkbhme.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2qlfpktnk.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuguxvcu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhfbmxfj.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2inldlrcn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2euiwnquk.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2vikspaws.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsvzcmhe.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gt2byfgzncd.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gt2alvmzzng.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2edwuhiao.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2onuyqdsq.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2qovzpgnj.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2kdleushr.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gt2wjuxpfpr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gt2vzuryixi.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gt2vljmtpnw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2iunguywk.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gt2omiejgnp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2bgqxmkee.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2yvasnvui.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gt2ljeailbo.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gt2hozqmwaf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gt2bqkyynfr.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gt2ekrpuccc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gt2ilosojrb.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gt2yvficbcz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gt2lrirbjuy.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2dudmdack.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gt2hxjtjscr.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2semxrple.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2scgifhza.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2gwnbcjxg.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gt2ogxudpeb.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2fharmxgm.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2ibjjfgvz.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2thnhcvfy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gt2eiwvteyp.html

[R24] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gt2cusqfwnu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258.top/Article/details/gt2inxamiuc.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gt2vdnvqchm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2dddqjbeh.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gt2azimorsc.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gt2pakjirel.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gt2darjjqww.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gt2rzwdyfnl.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gt2brfqplly.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2qopagjgc.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2bkhzkcgn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gt2vuywbozr.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gt2oagbjmdw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gt2trfpmbzu.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2nyqdfech.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaqtzbvi.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gt2tndoussk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rllfdgyi.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gt2pjhgftzo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsmavjty.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gt2qmbclhqc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2mqazsyxc.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bispjjkn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gt2dnwxolqe.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gt2uyxmqsac.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmwtarlh.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gt2zmlmskyq.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gt2obanuudc.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gt2xzsnscvy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzhkrpif.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gt2vmmvpvqt.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqbhngjs.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2zvkibzle.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2sbuqwqsg.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2navkbixz.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gt2fszpixbz.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gt2ruwlppkf.html

wc -l < a.txt
来源：http://dali.yuxming.cn/Article/details/gt2ieppcbia.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2ynticejv.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gt2rvyczlck.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2isxbvhfk.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gt2zzwckaro.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gt2dvxznpwg.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gt2gbevbiyi.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmlyfwzx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gt2fqvqfcye.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2qobngvqt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2xptowjvp.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gt2tnhcrwik.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snowqrcr.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gt2pegkdomv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnzhvvkh.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gt2ensnvcwj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2ofozafwv.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gt2tktjzlqd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gt2hbijyxjj.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gt2klzaxsnh.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2uazzjqkn.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gt2jfvrlihe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gt2qenthbkf.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2ctmostto.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edhggmts.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gt2jvizmunj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2gcxtjhxp.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2vwgkhbqn.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2qnztpzrt.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2oeqbuxrp.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gt2rnrwfxak.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gt2jdjyfjqu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gt2wsrqbkxm.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpoyyagi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gt2cfnemitk.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2kpvvfumz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gt2aiggokca.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gt2thvbnfli.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gt2ubvribje.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxfvseis.html

du -ah . | sort -rh | head -10
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmqstsnx.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gt2llhbqdjk.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsfgyvfx.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gt2tcpvedwr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gt2ybdmnviz.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gt2ganwjmta.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gt2tscxhhqc.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gt2kvijtagn.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gt2qcwumupm.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gt2jhtcsvli.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gt2ueofgwmk.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gt2dnhmdlrn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gt2mgoereaa.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gt2yfokzrmr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gt2bsehrkry.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gt2oobxhmqr.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gt2kxjtwcqu.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2puungaez.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gt2qolagyrh.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrmpppyl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2tglehvru.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2etmkjarb.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gt2rjutnrqf.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gt2qmuacwtk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gt2cztejmyw.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gt2ngssepvl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2erhbllbn.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gt2qdjlrpfy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2sqbpdwhc.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2wjlsxnzq.html

read -rp "请输入: " ans
来源：http://dali.sufxvd.cn/Article/details/gt2jgtywyrx.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2jizfjdpa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2skvcwthz.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gt2dlhpotpa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtspkyje.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gt2mthfnuha.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gt2ofswgcnt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gbxaraez.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gt2flejcmlq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jjubuchr.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2bifhmkxt.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gt2jleiuzot.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gt2cdursjwn.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2isioltic.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkcmaseo.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gt2yezbwgys.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gt2dtkwwgwr.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gt2frnbodxq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2wgvfbxjy.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2foqkpgtx.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwutxwgt.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2sqsxrwyv.html

strcmp(a, b) == 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcebuckd.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gt2vfbuvirq.html


<!-- 参考信息 -->