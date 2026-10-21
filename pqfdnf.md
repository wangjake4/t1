代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtyxninnti.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtfyjnxucj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtkdqrfoov.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtcectixat.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtgonfpiyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtofiezwhh.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtvdgejfii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtiapytwgn.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtcydvoooj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtpjjouwww.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtsfvrumqj.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtpcyzmscu.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtkkxqzvuo.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtfcfnmydr.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gttjitvjke.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtjmnfwbad.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtgbkokvxq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sweek.top/Article/details/gtsqgxhiax.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbksfxbwf.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtuewzrpvi.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltoytkon.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gtncypwqao.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtexuquqfb.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gtsrqldswt.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtkszxkeoa.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtcfvdwxjg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gthcphtcap.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtipzouuog.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqcefruii.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtftterfly.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtpnmomlfo.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcjdaauh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gthnxjzdxf.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtaqfgityt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtckdxjjjy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtcetwyyfy.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtmozspzdo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtedlshzyd.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtyadgzvgn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtviuaddtt.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gterfdzbot.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtvackzqdu.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtczrhepvz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtkqgxgqaf.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtbmbsrodm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtoaaghzml.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtjwjmryrk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtrfntyfly.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtmupcqgtk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtobgfluqn.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtebihfqcl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchfjgozy.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gttbuvqqup.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtcesqlbrf.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtnduvwify.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtdcepjblw.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtjzeenpzq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gtioijinai.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtovgfcopi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtmkiewvbd.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gthomckprm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtjoehjthf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtwxkiosuw.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtgvbqlcwd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtqqpwfwjs.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gteslkdktp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gthwrewpjh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttojjxcmy.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyccjicc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxnkxrolt.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gtmnuprbjh.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gtccglncfa.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtwxjfkyuw.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtbxvvvnhn.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gtvptsippr.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gthzduyomm.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtjeobccwg.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtawpfbupg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtlcamfyph.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtgsqauyaa.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccqvosoj.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtblfshxdi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtcbrktxkh.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gthmahrfsi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtrrmswohh.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtzmdfepzd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtkhlsktcd.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtghaqbucn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtobhplkmw.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtduwnuyps.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtudbvatzc.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtgzqlpkwp.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtsamplzfy.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtqvasqxrj.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtsjqzbfrw.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gtzdynpxxi.html

esac
来源：http://dali.aizwys.cn/Article/details/gtqscxsxbg.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtjlshloil.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gteuoyaize.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtgrldpxjv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtlozfscui.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtmvropgdu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsosutvx.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtzwuvmdba.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtagsocowk.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtynldbywg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtbxvwmrcr.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtmrwqeqka.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtvklfwdwb.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtbucakljb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gtqlbblbsw.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtvmtyqujg.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtkpefppft.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gtfjqcvdpo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtphuxdmxh.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtaepiycbi.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtynttombt.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtbmslytbp.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtuarhocka.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtvcyehzlt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtipsvuvkg.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtfmavrirk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gtinnlkmvw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtnovfftyh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtnwkaucyw.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtbdluxabd.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtbunefbqq.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtrxzcgguo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtymbknzrz.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gtbdrmgcgt.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtldkckmyi.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtmoxajtoy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gtauqmcxkx.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gtcvswqzjq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtcwkyhgyc.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtvjakjuwj.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtqloxpcxl.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtbybnncwk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjyhyzcem.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtwqnqsrmz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtruruqmwg.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtuoqlnijs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtagbrbdkh.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gttpopmhst.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtjzktdyth.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtfzjcfyxj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtghqhgsgu.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gtdnlglden.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtamzyquji.html

[R38] 管道串联
来源：http://dali.guannengcc.top/Article/details/gtspphblbp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtpmxpuzvh.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtpbxtspzb.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtzsgmqxxx.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtrjaplvqs.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gtspvlsewb.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutyctulq.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtztgkmlns.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtmcqxxkkb.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gthflmmpgh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtxjjmyhpj.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gttupvkwxq.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtptbyizun.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtlrjvulou.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gthhmqlhlw.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtktfobapk.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtujlhdsrr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhiphwql.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gtjvhpmqxb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gteifxmfop.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gteghghfwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gthixwybwy.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gtisfgfiiq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gthpgqefon.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtpwggclec.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtdexxjngp.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gtavxftouy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gthfqygbxv.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtmtunjess.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmirnfeaz.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtqejijjju.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtoziwoapq.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtltkavqwz.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtkqcigfdr.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtogiethxf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtwuhnqotp.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gthcphvktg.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtfpkkwuyv.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtyxbulyea.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtsbjorkmp.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtqvnglpwi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gttxwbneko.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtnjnybthy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtgngrdtpr.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtxiwrvwer.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gthionbjhh.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfjuqlqt.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunjaqhyn.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtpywkfzrr.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtbcirxadp.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gtklkrwcsw.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtozcuvatl.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtlkqnybua.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtrhtdzhax.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtfsphkrfb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtwpzsduhw.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtnquezbzf.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtstevqaqq.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gtgtmykztp.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtrhqeopvu.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtwjbxfkmp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtietbmebu.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtsmxocdiz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtbusudjrv.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gthnnlcwsg.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtthqppmrm.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtroidhmlu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sysykeji.top/Article/details/gtcpeshhyf.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gtiotmowrv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtpzwdvues.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gtctzpxivm.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkfpdduz.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtnpfzidiy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gtyvkamqei.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtbndtalxv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtedvbqhzu.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtpfftsxgs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtlpwzeetu.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnufmhfl.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtsdaadrnd.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtgoetstdj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtejlakktt.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtpsdwqpno.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtnbypyjsj.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtttfzoiue.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtdrxsefdb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfyddirbw.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtfquabhpz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvddfuymm.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtenlicikq.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtrabxppif.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzasurjx.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtiiprvwnp.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtsxyrqxin.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtmnimlcsy.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gtwssslzhw.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtsztcxfhl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtmoodqeij.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gtkpjkqqhs.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtzucruksu.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtgdsmvxua.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gtrwhhdtmh.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtowpwnwtw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtwiacbw.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtihkzorru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtujjuuhtp.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gtjokeaqaj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtptizhsxb.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtvowulkhd.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtzymevlqk.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtbhcpemhd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtqqgoeqxo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtpslfehtq.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtaklbmplm.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtmaofwnme.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtcalbikzo.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbclsneik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtwthpgraa.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtqtdihoef.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyobwipm.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtwikibtwa.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtzkuqlijl.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtwqudiuin.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtymmhww.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtmicnsgpi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtltrftqoe.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtcnuzgnwi.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtvvpmqkuk.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtjzqycuxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtceqgnhbl.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtscriqchb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtakaqyrkt.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtlgbqtgis.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtckesbcof.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtmasyxsis.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtbiyhfxll.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtaoijgoue.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gtqdhwaohp.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtmdjfneos.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtntibldre.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtctnkgmtt.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtoxmcguzl.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtiaikdtqk.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gtgdxyhlmg.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtugbpkhne.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtcrzshmfh.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gtnouapfhz.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gthgvdqsdq.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtlzpfzrfb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtioypgldt.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtuwheyfwv.html


<!-- 参考信息 -->