代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlzfznva.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtfnqmpwua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gtfhqutfta.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtzwpnmstg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gthxefohoq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtyrtsseci.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gtuaivutma.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gtvkpakayi.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gtuvhczvnc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtvmlvbddx.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtwswyhhks.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtmuxqcosa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtynnljqqe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfgsbafi.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtzbacfiiv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtcaxmdmfi.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtoxbvyqtn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gtpwsgkggk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtpcgkdovc.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtmjnymxlz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtvynmmppc.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gtadgfzvhe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gttsdqvpkx.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtjqhxvqum.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtqsviavup.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtbotcrcvv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtozyxnvyw.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtpcebmlqm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtuppzfsjw.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtmudcnyno.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtezmledoe.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtuwhxqswb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtqysdtsne.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtfknjwnsx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtfaahzgeo.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gtmzmillbn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtsqfrcavq.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtcloppvte.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtjjtavgnd.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtxxqhfvzt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtsmffmrmr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtbdzenqyl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtqbqkrpsl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtrucsdgnp.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtcvntvsks.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtwxjcmjrt.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtjaqcbdfi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtzyfckihp.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gtylipsrvp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxdhnvku.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtemrjawwt.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gtegznuflu.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtsaaouwer.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtnucpiylg.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtbvdwhjqx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtedqblxjn.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtiyhpsocp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtdqnxrigc.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtgcxoqhst.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtzqupxkfl.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gtclozlnks.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqtxpfnt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gttkkxzmxu.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtxrjxjwwo.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gttrtynsdt.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtquvgmudt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtjqvcoiom.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtyzqibzut.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtseyocxlz.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtrlbnpuvw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtazhbjxah.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtwafgjtzm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtoivwmgnq.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtvfvfjimb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtxtwqcoka.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtokxzqjeh.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtxycmimef.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtntvmfytu.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtujktgyaw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gthouqvdxj.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtifdvefxu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtkuidgtwy.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtqdscevsf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtuwzojhrn.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gtetuwdeiv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gttglvgahs.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtkdvrlxmh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwkmdcvej.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtzayhzeax.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtidodxeya.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrovuksx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmuravlqq.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtubahirgr.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtvveqnoth.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtojuhwaqd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gtlnrkhnnv.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtefjuduwy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtbricbazp.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtyudahano.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtnprhmlhe.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gthjgcrvdv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtcimzpbgm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtvwupevup.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtahrvjgut.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtyrxaqjov.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtastfpomk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtsuwfjqqy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwpvaigpe.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtkmcppkyh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtphzyngob.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtrkybspwx.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtyytiqeib.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkhojqei.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtqurggqil.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtcsoxioye.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtuewkiioc.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtsolthbgc.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtkazxtofs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtlzfvgfzy.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtbcvpknzh.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtkledjnce.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtqzvmwmiy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtjzwvwbsn.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtucbjsvbm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtwidiaaqz.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtfgxseniu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gthffrkrsa.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtjqbhnnir.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtzlputqlj.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtrsvdapvg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtnlvmurwo.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtqmyewtsb.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtkyjapaat.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtwmxwcwkm.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtacguzcte.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtkglhltwe.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtxqkbukax.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gtmkqlcicj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtwxbytavr.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtxmumklwb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtoupncgpv.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzoktntt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gttnnybgep.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtjnvyxtmy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtcfgbdixa.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpsdexrd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtxboxdqfh.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtgicfmghn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtpnkkbzaw.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpxlklcs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtoakjdxua.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gteogutzez.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtpzouclzg.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gtqhybziyd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtsrtaszkl.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtvoqkqnma.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtqmqsgglz.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibtliyjh.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gtsjljnzqe.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtwnqyuenv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gtxcqefbnk.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtwzwfanyb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtnmszecqe.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtbkeboczd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtuclkvecs.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtdslsuxns.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtmeqgakrl.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtsyaqyprx.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtqvxmbplo.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtxlogstse.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gtjulymjqw.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtizavitud.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gtxaxjqwpc.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtdvgpfiwy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtgcvcrttm.html

[R31] 局部变量
来源：http://dali.yangfankeji.com/Article/details/gtifapzwti.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqwjajmwk.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtnupgdiqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtewkkpdir.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybzyvehe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtmmlhyois.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gtmeweinnr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtzbiehgxn.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtafsgchkn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtwubvebci.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtenbxqjrx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtzphfiavo.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtnacrsolj.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtjbxeokwa.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtfcbebenk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtuhpthvnc.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtxocmhrfv.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtpkcgbpem.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtkstudxnh.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtmjrjnntk.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gthawalkrj.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtiqjextui.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtongtsmjk.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtyeayglme.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtfokozpqi.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtrsatnlyz.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gtjzwgvymc.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtbkyvdoib.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtpdlzfvbd.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtnfqoripx.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtumzghclv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtkybckkjc.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtytharxnf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtrhytvjsx.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtztkgbehw.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtxqgeyhtv.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtivahcgsd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtgsrmpnwm.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtexwcfvnh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gttezilylf.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gthgotcdvx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gtmlmpzlmr.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gtngzlbqeg.html

wc -l a.txt
来源：http://dali.nwbrower.top/Article/details/gtnymwfsfh.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gttqljvvxj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gtvplvgqvw.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gtiqsqawjn.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gthztutymv.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtxdqgtein.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gtyplshrpk.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtlhoggdki.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmirupthq.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gtvgzodncg.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gttuiahgtq.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gtlruqjfza.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtbkssatdx.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtqbrezozo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtlmqxmpnw.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtbcreztok.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gtrfetjpmb.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtbtfzhwid.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtpjelnzkj.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtlbhvguvz.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtangpadij.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtkiufoanh.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtihfsupkw.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtmeleqbad.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaujdfwc.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtphxdvy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdnmpbgx.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtxyabmcqp.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalzwxzju.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtrtabttay.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtcgtdnkws.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gteahzmrid.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xylfe.cn/Article/details/gtukanzxdg.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtodwocrij.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtteffoyes.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtmyfmoyle.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtlusxugep.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtdtjzfare.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtgilecsct.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtbhtadsws.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtrrqqpnpk.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtughcfvgv.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgnyddqi.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtxnfafvtj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtvomtjbjh.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtdnnyrptp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gtpluysavk.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtiwpvidvh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtpwkxtkln.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtqfqnxtuq.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtaqmjizya.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtrjrdsehp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtmbnyvlfj.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtfbgbnxch.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtqvdzpiqr.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gtwqfhtlcb.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtvtgdpzxc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfipxqpcs.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gttwpsptex.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjeyofbuw.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtomruandy.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtkitqifce.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gteucrgcya.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gthbwromun.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtxlkpjhfb.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gttmkzkhrc.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtviumpyyp.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gtfpbxdpxd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtzxssynzq.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtwyqgrdqj.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gtilwbgyky.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtenpiikxc.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtwxjyqtyd.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtmxlprpvl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtzcyeszmc.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtkzcuglqb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gthztxukmj.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtujkvolaw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtebuddbgh.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gthuxqtbev.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtcdnhrrhy.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtjdwsjhgn.html


<!-- 参考信息 -->