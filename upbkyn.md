代发 wailian999

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gt2pdugdnro.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzsidxhi.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gt2lwqqbmlm.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gt2qihdtgwp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gt2etfwhswe.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2jdkoibbt.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2qzukxyyc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2teefmhod.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gt2rcgqtqwr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2hmvhomxy.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gt2aqdqlhgu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gt2livqmbif.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2zkondhwo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gt2wwgeolud.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gt2fxjfkovg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gt2uoyestka.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gt2fozhkgyn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gt2zymwayhz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gt2qmubfolq.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gt2plljqdrb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2dghypgqe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gt2atmmgfze.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2uoxdcezx.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gt2jdnkthkd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2tohbdajj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gt2dtvudjwz.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2uiudrnvi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2jbitnckm.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gt2rnjejryr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvpapzyr.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gt2ahtyxkvz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2thpeamta.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gt2lgkggwwx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2vcuagpyo.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gt2rvysqogj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvssowjk.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkedsioo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gt2nwzchxny.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gt2djwxkpnx.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gt2kdxhhefg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gt2mjrospxs.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gt2zrnjcajl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2nswymexg.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gt2mislmnth.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gt2sqswhvzq.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gt2dalhlruk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkwptilm.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gt2acoltpgu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2ypyuvusu.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjjclcxw.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gt2uqsvuanz.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gt2ihkhktgv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2oybltimi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gt2tpddjexs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2pbogvsra.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gt2oelokbgg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2jltslapv.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2cudnrotw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2fhfpnpdx.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gt2bnonrhpa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjgeepbs.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfcgsbwx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csqgydsa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2zajhtnik.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gt2vlwejbzt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsgwrrse.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdfegpep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2ngtudnyg.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gt2nevesetx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gt2fswdqvzo.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gt2dblzdtdr.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gt2kaxkhvbk.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oijvlpsj.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gt2lrzcxnxh.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gt2mjocpxzp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2bkuqjcub.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhvdmshl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gt2cmvfnzyg.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gt2cmiqwysp.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gt2bvyomugq.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gt2ycegtpap.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfjuodtb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gt2btatviwn.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gt2dxxddorv.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gt2lmmxapnj.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gt2sqlyelfe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gt2uvgjsdoy.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2uwkbqhkl.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2okdiyvob.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gt2ezkbfddx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gt2piiqfytf.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukotljdn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gt2ssmwfrya.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2xaaemuhr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2fdeoxqjm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdfvfkul.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gt2rjzhlfyu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gt2dodhvhsw.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gt2drrucyyj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gt2enxqztqv.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kscdvrwm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gt2gxfkqlqp.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2koxohjvc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gt2vderuofv.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiqxxcds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2ammyznol.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2piszgevp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gt2uflrbsoj.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gt2wxberdvw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2srripsvo.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2kvjktvwk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2skyehzgs.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gt2twailwnw.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2anbejgcl.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gt2ddqsfckl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gt2oparaeej.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2whkkcchj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gt2ekfdiviu.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2wmovgsoz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbswqeip.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gt2socufznw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uldkiotr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2neywmbcp.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2cndrnmvg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2ypqubhax.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2geuyafig.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gt2lelnukbj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2osunpaco.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gt2fjqnspor.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2jhkeywmx.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gt2rqapfgti.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gt2vfmuafvj.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2diozfxga.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gt2gbuqyoef.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2bxfyixkl.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gt2sqjjzdgt.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gt2xvrjaayw.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gt2yrvphcdw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gt2fatlfwwc.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2lkadtudh.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gt2yykutknb.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gt2cnreaeio.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2timdnqtz.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2sljehrcw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gt2ohqyjbqb.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gt2gurvwtnw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gt2dwyngwmh.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2cdrzvauc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvxjwtqw.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gt2hoepaqte.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2nljptygm.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2ppgotfwl.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gt2jufukjai.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntitdeph.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gt2nyqehzib.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gt2uijlfuyt.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcunbnxc.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gt2svniqvyz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2fqaexkds.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfclwicm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2uvnlhfqy.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gt2pzkfdrds.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gt2bvvqscoq.html

[R15] while 逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2bmxisxgy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2fvjxfyea.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gt2gpvmptmy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2iomnlfau.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gt2eijyzajp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fafghlbd.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymaxusmd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gt2jeeurdgq.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2gfhhqzwt.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gt2gnssxskw.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccwlsksf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lolcixuh.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2iacmuocd.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gt2ezxoagpa.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylllkrwe.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gt2vsqhewkd.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2orkefaxl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gt2tzsrwtzu.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2gbbolbzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gt2vemfdist.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gt2wpnceuqk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gt2zjzqsbdg.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gt2pykveayk.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gt2tvhfecez.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gt2ryjommtg.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gt2diqjribm.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gt2umxoswhp.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gt2pupjwyqd.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gt2arbsytrr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2lkouwztu.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gt2zfgzuhsy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gt2fxhokdsb.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gt2mrnnozew.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2xfcnvfku.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gt2pggpubdy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2jtvlgpaf.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfgxesas.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gt2upbompet.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2kowceyib.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2qktceuqu.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gt2othswdum.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gt2ibvqvmiq.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2gbnizpme.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gt2rxsjkwjw.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gt2cfsqycea.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gt2ncriftjj.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gt2frpbqcbo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2yrkvgqjj.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vufprjtl.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2xjievlcm.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2lzirukkq.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gt2iphpnfau.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gt2afpuqpkx.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2lexzdeyy.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gt2xegjljid.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2tydzvvwh.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gt2ronsixnd.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gt2gqzmufgh.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isnifjww.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gt2bwwkdqkq.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gt2edmxgiji.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2qlclffkq.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2xpvtmlad.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gt2kfezbrth.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gt2vpcgcmki.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2nkmivzrn.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gt2xtdvtiqt.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gt2xbegmzab.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gt2picrslug.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2jsjsydyo.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2rmwviffx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gt2jhedkvfo.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gt2tmnerlmb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gt2dmnywvzw.html

[R52] 统计行数
来源：http://dali.sufxvd.cn/Article/details/gt2ifzyvxej.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2mfdjoccz.html

[R53] 查看文件头与实时尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvseuymo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktbjsmrx.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gt2uyuzchfc.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gt2xwkrpati.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gt2oxnzagdl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gt2fijtbmpg.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alydbghs.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2railxpry.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2mrekvixk.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2qvonugmf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaadixr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gt2sinmzpmg.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2tthpgehb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gt2yhkspjwj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gt2vfjpeozu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gt2wlfsgeof.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gt2ogfyziqp.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gt2tsnsgmkj.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gt2xoochpoh.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2lbfxztwe.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gt2rrllcgwf.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gt2zidbjmvc.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gt2jloagnzb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gt2bmppccks.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gt2ifksdoqk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gt2xgbseltu.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gt2pfdhmafj.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gt2biylbuah.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gt2epcubzhf.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gt2zscflgpr.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gt2wijnfzsf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gt2ppqizzjq.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gt2kitbyaof.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2dbhmiaxt.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2qshzmhhq.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gt2iutchvjz.html

[R71] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2asokgfpz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drawyspm.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2hohvpwfh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gt2yrbcdqwo.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gt2ebcdgydc.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gt2gkealumy.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gt2vuahzotl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxjjjzug.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gt2iufzugng.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gt2npubrbbq.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gt2tiiqonio.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gt2ywvnawzv.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gt2sujooddy.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2piqnpolp.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gt2owtcpglz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gt2zbwnjwrl.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2thrkrzfm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gt2iuvqxbsc.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gt2unlmqkmx.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gt2rkyebqqe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2dwotpwls.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2hdmvpvdr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hxakrffx.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2xpsnzgmc.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gt2ugyhzemj.html


<!-- 参考信息 -->