代发 wailian999

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtbtxzwyrc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtuvujalyl.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtaparaxxl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtgjiueaef.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtzbyhkfxp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtbywxapfq.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gtipkjtqqs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtlfjgqtkr.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtvgdocjyc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtphjrahzj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtczoukdiq.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gtrgcztbum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtarahzged.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtrejhwgln.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtkftwluct.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gtlboxjwir.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtgreczher.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtksnqcvbr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtphcyimzo.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtphqdnknn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtyvmapnga.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtwcdzanut.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnapajmye.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtovzxtgro.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtdbsgzzpn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtnubqcfpd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtdgqwnenq.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtkftzugoj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjfseznij.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gtqnummcvk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtqwedbouk.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtxjbdsabb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtlkexoxwu.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtyrxnafts.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtifyqmckh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtuthibyva.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gtybjuevcv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtxkjlsjhf.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzvstklz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtsepflfsa.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtjgtxodgs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtdwubhofg.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtpiaosdtp.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gthzhaegum.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbwaumnn.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmxsqcyx.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtmlinhztn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtgydrabsk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gtudspnifx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtbfsjbmva.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtxzezgucd.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gtesdgtwie.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtbjuuwihc.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtsxfkevtq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtfsqqvrry.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtwkgliwvo.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gtgiorajer.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtylrmtlos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtwknifcay.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gtrvftiphk.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvltxnaod.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtxeerkkjr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtcwcfjlbo.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtqjqlmbuv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gtxrwswcfc.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfehqzcm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtbtyiverl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtvgurslxu.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtfxwjrcpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtbtqfrsrg.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gttuouvbzz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gttdtpriny.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtqdwwdczh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtkffgxeej.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtqhajorve.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtsnvvihag.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahwjyfdq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtqhsxmkml.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gtvlpgepzl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtoubfunyw.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtyuhktzxf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtjbwxxvah.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gthrbsyccy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtnhipjtby.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtpqtvshqs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtrnwihqdg.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtrpbhusov.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyrvypra.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtuqygbzsi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gaohongyu789.top/Article/details/gthokjsjnc.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtrxogdbaf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sxryk.cn/Article/details/gtlmpblbfv.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtssbrkhoy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtxacumejm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtekxekilc.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gtbizfuqwp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtyszdwsxb.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gtlyhccrby.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtheijlnyb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtuebumqhe.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtrdoikzso.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkxbiywvx.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtksrgdjrg.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtehenczwf.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtbuopacih.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtinyemgoe.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtmvtshajm.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtlltoxxmi.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtgdhoigzg.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gteffllmcy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtwyhzppru.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqatqlqh.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gtsrafskxz.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gtsxbzvnsu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtprubjggh.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtoglfbuld.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtkatpwtsv.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtstikhqsv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtnwbuhktn.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtjkbsrkto.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtvxqarlzo.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtvnrnrctp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtofhuqhui.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtaeywjecg.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gtgntbdelu.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjigbmwy.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtjttetptw.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtjfiuiqed.html

esac
来源：http://dali.yj20258888.top/Article/details/gtbzpfjwcu.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtbnbfyubr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtmlzgvxkd.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtkaziruxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtngsoeknh.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtkvwwdvmt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gthewjlteb.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtfuvbvkfj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtlbpjmqed.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtcnnbyzfe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtxfiewdyc.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtcaoucwrv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsevjmzfz.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtozpppcwy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gtjkboeont.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtgawrqbvm.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtowafprhs.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gtiryvxanb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtbrngouxd.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtlkoawkhn.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gtxiqehmom.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrucqxgu.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtepsdmvyv.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtuxwzrtoy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gthazbvrad.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtkqjgxedm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtrstqsdgc.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258.top/Article/details/gtbnlatrki.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtvsayfzjj.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtyjtdputl.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtuwozbbvy.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtqenwvorr.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtsdncwope.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtdeewxrps.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gtmzufjcxq.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtyiutyort.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtizwxapzi.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtxjqfrlpr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gttjgjhbdq.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtidqudrpv.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtmpdrdnak.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gthvgxwerz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtilltnklp.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gtfglsaftb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gtdfpuhrrf.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtbobpqmeu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtolruofxq.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtizbwmaqo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtbqqcxclc.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtqvyyoawx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtfeksbedv.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtlmkpoqkk.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfomqtzcr.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gtxhilelxp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gtstibxqoq.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtyjjvbrxw.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtrdygxkrl.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gtsqhhtuce.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtkhcvtpzr.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtbikffdkp.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtfxsmktcy.html

[R42] 输入重定向
来源：http://dali.yj20258.top/Article/details/gtiqejxkxb.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtcwzgqfdl.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtajfocyir.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gtejvljzie.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtnwadxofq.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtltpbqevr.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtthowdqjf.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtpjylhljn.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtrouqwyeh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtuxeccpev.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gtlhymoqnh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxdqankw.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtfszgbhri.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtswbhvynx.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtzlruoryo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtqgombyha.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtlivyqusa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtqjiawejx.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gtcqfgfmbi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtdgfckdle.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtzqtdlyak.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gtxzinnlbb.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtsglpxfqa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gtzoolctqp.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtbttcrcmn.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtqgyykbbm.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtrtdslwsv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtcfbtgjro.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtptpkuwqb.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktfxwshj.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtkkjfjqgw.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtupcavyty.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtjljxszfl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtrrsibnco.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtmwcqzxhu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtqdwxvcfc.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtqglpwwlk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gtihabuuwr.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtijcfhrpb.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtxzvkcqzp.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gtxqqwviby.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gtvwrvggbw.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtmmtrztyr.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtcpiwkpiv.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdturtcmy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhoulong.xyz/Article/details/gtvmhjhtxp.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtecfxrqph.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.snrcjt.cn/Article/details/gteoexdobm.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtpzrbxnfg.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoplcjws.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gtgjnbyijz.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtrrjjwthl.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtpgwqegbo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gthbmgbhzh.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtqmlacjlb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtknhotkov.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gtegepvzha.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gtbdckigyu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtnvoebwun.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtqspqaabs.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gtgmbxhkob.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtqosdvoqb.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtfxjehjyd.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtljhysxqa.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtackuejpk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gtmmlvjqyc.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtumnnjddp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtwlqbsjbw.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtisfezygu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtnrsmrmsh.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtzwzcfijw.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gtsxeuufbj.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gtdxexbuai.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtnagqxelc.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtucuvzrvo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtqjngjslj.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtwqhazcif.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtjmpjzsjg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcpdkxbqi.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtwvahjowx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkgszpdrn.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtteiqieof.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gtmfwcdrga.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gtvdvufkpp.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtsghgpbsa.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtrckksjdz.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtcndeojxj.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gttzegadtn.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtajhiqaju.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtuucwwgly.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gthhxdezbn.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gtsqqltizc.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtklgxoyvx.html

strcmp(a, b) == 0
来源：http://dali.iojbl.cn/Article/details/gtuwijskos.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtdneumfzh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtragwnoku.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtlbojgzax.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hammf.cn/Article/details/gtgdksnyjt.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gthiarnpmt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gttnvgepip.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtzvkealjh.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtcpgaoqrx.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtywfrrnmq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtccsrrlqj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtewxrvlnx.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtmdiahggk.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtxovaksbi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtszymkkhc.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtcfwturhp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtmdxgwhzp.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gthawbjyor.html


<!-- 参考信息 -->