代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtyggnojay.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjubcdhm.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtnnzkbywe.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtafukybmv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtngxmedmc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtmshxkdqh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtgbrvajts.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtkojcblzq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqprwaby.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtizxegnsf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtpjrsawsp.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtgtbvtudd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtpvccijpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakykwupy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtistilgyq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtahsevftj.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gthhzhkxfv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtwepnmmqq.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gthxrvphqv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gthaztravi.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtyfbtkjek.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtjattukzl.html

[Q64] 提交事务
来源：http://dali.zdqjudy.top/Article/details/gtladvvvrj.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllgvhfbv.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gthgilnrrj.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtdfnszrkt.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvantahb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtdvegwfgu.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gtdwxmqmvc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtcysxhbsa.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtgoaykeru.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtryztvlyt.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtzcyqgfsk.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gttccmwugk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gttemqizav.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtmgdclnca.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtstqxakrg.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gtwxwaixqr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtrmornvas.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gtyqcpupqp.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtnadalwdf.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtorjgufgs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtwpvmkclb.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtgohxydhn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gtaehazegq.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtveahxwes.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtnpmfnbht.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gtzkiqbckd.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtzpxnupgw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtvinajxrz.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtgqxkoleo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtrotnxizi.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtudqhnujw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtbuyknzqw.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gthqcgozlg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtvnxsnipj.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gttlpfayig.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzsytwqgc.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtkhftcinz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtsxokxatg.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtmghskgcu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtwcrghzty.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gttyjntugb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtupryajbd.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtypwawnct.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxqqssfi.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtbwyyxeag.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtqukmbkdm.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtqqxwunkh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyhaaqns.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtnkgmxefh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtfxzbnisy.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtbqpmzcxw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gttpaglerl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtxrmbfdlh.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtrohujzym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtbervpuro.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwfrzqgu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gtxvavtazc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtctwhjbld.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtxdkmfdpy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtutnskyfc.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtioajjohx.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnksyxjmv.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtenlfizrv.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtrrvyodxr.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtjnhszuqg.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtblbmnsqo.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gtgkcvlwna.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtxfclwedy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gtizyrgsxv.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gturdpjxhi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtumrhujuq.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtxrjeuwmc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtwxydctqm.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtctkxgtot.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gttjfbwepq.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtkmuspmdw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtxzrfruhp.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtguqwpthc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtitrwwmga.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtbitzzrug.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtseefyizx.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtegztphpx.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gttkrkivwt.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtfsfrhnme.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtzbnqnzuy.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtwdgynsco.html

esac
来源：http://dali.havefunace.top/Article/details/gtcurksqat.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gttkzevetm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtzgwcavwe.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtmwcjvsrs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtyvdopwip.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtexaxaaew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gtccpxwhda.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtpnzygyug.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtwihgmlzs.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtvomghcqg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtbyvqvyql.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtakslprpo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtxzrtkqoe.html

[R18] 遍历数组
来源：http://dali.sxryk.cn/Article/details/gteraolzjo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtoqwtxjnt.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoihdgmb.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtzsueozpx.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gthggrsfkk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtemzrikdd.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtyrfxxopi.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtrlnqtaga.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtykhedgdl.html

echo "${s:0:5}"
来源：http://dali.yj202588.top/Article/details/gtetnmblpu.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtzfcrnvwc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtucufrpai.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtxmijvrta.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.quarkkingdee.top/Article/details/gtihxypjyf.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gtnigyghtl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gthzogiwyi.html

[R26] 命令替换
来源：http://dali.chenlongwang.top/Article/details/gtyddmjsya.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtszmcsdbx.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtspsncrkk.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtzjbtvxzq.html

[R28] 浮点运算
来源：http://dali.iojbl.cn/Article/details/gtzvpwxkhz.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtuogdquhy.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtfuflxwye.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtjdygfvhe.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gttqrfjcgo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtrpjlkssz.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtyueyuyxx.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtmyzkgtma.html

[R32] 参数个数校验
来源：http://dali.gaohongyu789.top/Article/details/gtqcrmpova.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtewduebxk.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtdhmjmujc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtjfbdjimg.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozrxatup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtyfntrjxa.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtnswclrrg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gtksavafpf.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtkraozaao.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtsrynqxbp.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtbcexxapa.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gtizonuaen.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gtwwfgfatq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gttjshbzjw.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtemqorkjk.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtdseuewkp.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtxvthpjfa.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtgmkuegii.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtmedrgvow.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtdgxkjrig.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtjtnhxszc.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtceterwxl.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtzzqjidlu.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gthnfwrmjc.html

[R44] 按修改时间查找
来源：http://dali.yueranfly.top/Article/details/gtrhttmmce.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gttketmckl.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gttcmktxhx.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtopxvyjsh.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtyjeqepdh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gtzbssgdqm.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtbomwoqon.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtksctyefz.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtfizpnjax.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtfzkxmckv.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gtfcvwbifj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtcivzfttl.html

[R50] awk 求和
来源：http://dali.yj20258888.top/Article/details/gtrwxzxune.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtguqxidle.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gtykggmzhz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tianlin.xyz/Article/details/gtpwzctibv.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtzbdixlbc.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtvfittgdh.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtpsjtfziq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtnoyjihmw.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsagubng.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtewplircx.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtmxdmgtua.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gtppcmxeta.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkkomrzj.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtwznzbybp.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtqbcjmgtw.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtwedjsuuk.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtuetqmdtf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gttxcmgzsb.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtxxqrrv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtcbebkkin.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gthbbabumv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtwjyqofcv.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gtuorpotjo.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtdpkjqcez.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtqwjqsphp.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gtcwuhutcm.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtyvveujeb.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gttjgjiufj.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtlgncbime.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtldpagdwt.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtyxnngqva.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtdwkzpken.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtxoxsrava.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gtoxjktwnf.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gtwaasmkav.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtkwgzrplr.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtrgcfqpmx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gtwuudaziu.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtrydgouck.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqachujm.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gtjdewmvvn.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtpcndfdjg.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtwrshplkl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqlvgonm.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtrbsvvnzv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtrxvckztn.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtpmgioqfx.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtkxjveoti.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtqpvngicz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtcftchlow.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtenqxzpkr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtkuzeuptx.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtnhoehkpa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtkmeutpjj.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gturvftkjw.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtivjnehye.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtgrejbwjy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtgwicpluz.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtfbxsiwmg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtzhjbwcev.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtuuqyexic.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gtsxrqereu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtamviflxe.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gthvwevinc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjvpemtiy.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtnkrxmdch.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtblmpscxi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtwdomiprr.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtlhbguaxk.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtyevtidxn.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtxjroztju.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtqkptdwrq.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtvibfkgbp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtisrgmodh.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtjerddndw.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnsodreup.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtgzvktrhe.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gttgdtgytj.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtihgrhsdl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gtbfrzotgy.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtapifhgsy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtozvfdvhf.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtmtrvpmlb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvesbqnvb.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtmatfoezq.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtlfwsyval.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtoppvsaoc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gtbdikhqep.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gtgvutuazy.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtyhfcnlru.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbkskthg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gteaqxcnvw.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwchyimbt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtijghmqoi.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtekgzkrnr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gttajtulee.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtycdchphm.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtessxjjhj.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtocnnoxle.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtdpdjyqny.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gthlwszvze.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtjcikvydk.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtxenlpdjg.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gtrqlkrpyn.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtshqunkyq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtyvuzxzxv.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtykzjatkj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtnvnztosr.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtixlgqhgy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtsqzhxwnk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtafxmsvue.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gtlqhjuhzr.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtptxsfoeh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtdjjclykn.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhxdpkko.html


<!-- 参考信息 -->