代发 wailian999

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gtnbvdjoye.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtkeudisnf.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gtbtejqbje.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtzhykzwdg.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtnsxnlqoj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtarxryhse.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtscldknme.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtswuinhfk.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtkgjaptvu.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gtxpmvvtmh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gtnubvysfj.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtzabgndsx.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtenmunkmw.html

[Q71] 查看建表语句
来源：http://dali.jinghuilouyu.cn/Article/details/gttxhdkgsc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtrwqvuawl.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gtxbodcejz.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtayzilhoe.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gthcyujmol.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cheryme.top/Article/details/gtvosdtbws.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtwgleeuxw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtsscpxtso.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gttobuwbcv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtetxplrtn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtcgioodpd.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtzpxagfmd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtrecikuqz.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gtfzpfousq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtawjmxjic.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtopajhtzj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtgilcrxlh.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtimxkqptm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtisgbddsq.html

[Q80] 字符串截取
来源：http://dali.yangfankeji.com/Article/details/gtzdfyltzs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtomixpwvx.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gttagzezan.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtnmudmexl.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtmiprhuuf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtplojntwo.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtnfuqlsze.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtizyroygf.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gtwpoydbtg.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtzbgogcqc.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtnsfmnowj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtuzlkwrts.html

[Q86] 读取 JSON 字段
来源：http://dali.birdmap.top/Article/details/gtzbhlqbzp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtvdvjmbuk.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtbizgercp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtulvscpda.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtvhexwbrm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gthelerirq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gthxngqfyq.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtnfrazauq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtjtcjnppw.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gtikjirfld.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtlfrguqks.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdfoxugl.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gtlopigpjq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtogozrele.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtubuxsrsy.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtuodwrdeo.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtltanyjox.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnhuhceu.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvegyhgfl.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqghqpdo.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtzboutcwl.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtszcnbzpn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtcrqicrwt.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gthlsztwuo.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtsslbzrwb.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtfbzyrcke.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtnqltgfgq.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtjnymstyf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtlmjebdpf.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtebhaozil.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvxxmgfa.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtpewulgcf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gtzmanvtul.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtdyqrnzqz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtdypbelae.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gtaynpkegc.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtitagdgng.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gttxmtthlx.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtllacggbm.html

*)     echo "未知命令" ;;
来源：http://dali.nanxinkj.top/Article/details/gtpzygliex.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gtqicaprep.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtmksjouam.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtclxqshct.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtghdkhnyc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuinqtqy.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtqyhprjjd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtuqawygia.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtuypewszd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtiksdvbib.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gtepibezih.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtmpxfsrbr.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtyzjhhowu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtrowhiiyd.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtebtxpjep.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtkqiqqhvh.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtbvydmhca.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtpddoxpac.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtqirgzqdd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtpsftbmzn.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtjxwjxmhc.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gtbtujgolo.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtwishpoxb.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtdlhdsgza.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtnwbpyqgo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtokcwjlmp.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtbteglwlk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtxgxopiwl.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtgxashgrq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtgptabbcf.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtdqesgncg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtexweveoi.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtyykaqeia.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtdlnyanhg.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtkvmcrgrg.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gttrtfdwmc.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtxtiauzuh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtexuduinp.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gtqgofrvho.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gtqsoqyrgp.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtursfrtlk.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoypuypix.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtnvlkfnlt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtjfvbnkkz.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtyeazzsec.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtdyzzgbur.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtzhzfgdsg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtcxeqrgsn.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtsrohnojn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtiwjoovrb.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gtikahmsju.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtdbfmifdl.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gtguzuccjm.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtbbykxmgt.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtufzdrnhg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtxynoazes.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtbkparaup.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtqvzmjpzp.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtwarxdgos.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtfdadqwnd.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfswkcuf.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaohqgno.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gthfwbvtlc.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtczvufbrh.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtmizkhksi.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gtpecrovbg.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtnsjqmxco.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtubyffijw.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtnaiwdhjr.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtksxxidwi.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtqtefafbo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtpgcbyyem.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtqryhqoor.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtytdcsvpr.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtbnqnstwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtjhgbagpw.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtuvkqvawe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtqtvncidm.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gtnfeizbqg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtnyrevvev.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtmkneeqef.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtcktnlqke.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gterxefikj.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtqribwubn.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtequvciyv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gtszychgdi.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvwtslgy.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gtrvrlephx.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtphppcals.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gtqpnqyuym.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtaeqaocrh.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtixrujeoo.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtfprqzaqn.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtsuprsouk.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtpeoymbks.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gttxlhbenv.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtplrsxkof.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtzdennrem.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtskfeedwh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtkkiknfop.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtwqbvmtcx.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtrawwyhji.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gtckwgylxq.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtahtruvvi.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtimynrdzw.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtnklpdgbl.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gtehhiqrhk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gtfbwpvoxa.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtllpwnpbq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gtmipoffgm.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfpzxodx.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gthleympbw.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtblrdavdd.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtivfexmmf.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtylqgmmfc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gtdpgemeeb.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxrhkfgz.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtfvuidxfs.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtldauixjr.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gttggkoghc.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtyogsmxwp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtsetfpyjm.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtwthvhxox.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtrcpauvrn.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtbvrmbwma.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtiqnrdxpc.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtqzruzuhb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtbsqwgszu.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxnxxjzo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtxbijeeip.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfqxrrmk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtpobaccji.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtfxgrrlfz.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtxtjqwhyl.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtlmqnwvoq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtqyofaklo.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtvbdlawnt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtrpvsgbjh.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtlmbcsqnv.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtwgudsjfh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtysgbdeqp.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtrnojqoof.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmumoxwas.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtgkkkxsut.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtwqpfwlhb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gtkznrslmc.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtyqhpkqqc.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtkrsnlefl.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtwksrwqid.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gtfqjjwoxq.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtfrunowja.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtwjgsfuiv.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtcshdoeyj.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtfgoizkss.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gthnzrxdxf.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtmdestdzs.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gtzrokhnqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtcvcffeel.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcytfshzu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gtqpzankgu.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtfbunbtxo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtnkbcnitl.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtotpcttoq.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gtzwdsarrq.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtsdqazaha.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtouljtmxb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtdmjfxuzi.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtsgvugwji.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gthmbrgsmf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gthfpyynpi.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtzyeocatl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtzzzjrpbt.html

[S14] C：枚举
来源：http://dali.xylfe.cn/Article/details/gtsddahpkl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtqoetmybj.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtphptpykj.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtijfjluwh.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtkcfuaalh.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtsvxmpzvf.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtxkoqamjl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtxxrapydz.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnjecsxm.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnzhdgxd.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gtiqtuxwnv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtmutwmouf.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtomhtbqva.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtmwrfwtaw.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtysguixli.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtvmegfebr.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtoreudxjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtqmgtjahe.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtciaufbvx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtovgglkro.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtyzbjxube.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtrhxjlenh.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtlgbnbknu.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtanjacdni.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtjnorxndr.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gtmcsieddk.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gthdrxwuro.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtbqxxfwff.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtompvfrwj.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtmaeyxtns.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtcuxgkwiw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtpldfrisn.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtuhqitert.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtnhvpbzdf.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtskhvnneb.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtiygsojxu.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtywvniipa.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtlermnvsd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtderlgdts.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gttsihffgz.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gthrzrzjkm.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gtfwwwnzfg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gtsxoowbtb.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtattvwdja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gthygddjsf.html


<!-- 参考信息 -->