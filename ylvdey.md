代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xofodcaz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2heaiudsp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2eokumcyu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcbglfo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfwmgjg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xidcleys.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkrrvxm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqufyoo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzdctdi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaxthwu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiziawr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqgdcrm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djbezlmu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jellnfpn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fongsddh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oijbpoop.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfcvfad.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tpelfpem.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tubtrqfw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdubzoi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gksyvvhn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2himptvda.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eofooknk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2npzlxwtq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdkspbu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2klxxfjzb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkzzzvi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pzovixis.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxhslsi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpaezky.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nswvpwyy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtcfuuu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyogiua.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqmqbta.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2niebcsat.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txqqxhqv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bosiclyu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgozzxj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jemfhnvb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkmqddq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rghhuies.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2plvrbfqm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2asjldptm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zldacyrd.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdacyxl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsnepay.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfnllsf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sxadkyic.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2efhthisx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsxeomz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpqlcdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnuswpo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiyehof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psjkzlkd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ubopzvyz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fdooobpk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2citrxjmz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzwvtxh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2plxbukcz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjhxjnf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdpknlm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zctcwwzj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2stxsrgfl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwpukum.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqykzafw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kakeegen.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spdrohez.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrbsarq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rvudkwtq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfmbjlx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dtawfasl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pssaaiwh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuvtfwz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wyppximv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jmifzicp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjbabav.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2axtsxzis.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2blimandg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzphwht.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwujnid.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nliqgoui.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrkfems.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujakaups.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uckgnzsr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eshcmebj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlniqbz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfqbzbq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkckpzt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzplrhic.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjskzbxm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaybsor.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tawjyuov.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzoessp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xoordazf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrwyrjx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwxlwul.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgcrjdb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdzvhyj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfyseuo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsnxafp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhlcdkc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gveehwed.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2noyrnkkd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmtayyw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nruiybpt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqmunko.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nszelden.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eedynqlc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xixlhics.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ieotwnxz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnophju.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwxsejx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2itooilmh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmkipnq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzymseq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjwpojt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2enwhcdov.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2crcwklts.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jivsrmid.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwxnfqz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bluwlsyn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vomyhpww.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dilwhjje.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2awwhwdoc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2upcvjhdd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gwentygi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxajitl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2avltbhoe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2enpifvya.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkrlvyh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvbnrwe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llgbeopd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghovnfzn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwstqmx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2neyoxkcj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wiftfyun.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsshhvp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uoggzote.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrpozxi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uycnbzlp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmrgmrg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzqawxw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmftkkz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgvrmuy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjhlwpk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwwgpjn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2clbphjqf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2koaumikq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yhivkkzg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdahmnk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfxwcno.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjkmhtm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfajgqdb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jaojrdwp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cajqluvj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rehkizpw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfmogcw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aadznxih.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvxkyis.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2knfintcq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yubsozdz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwswqia.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egzpnvdl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlqpjmr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hukmiyby.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcrhcqt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ticxlpqu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2arskenzk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gofalldv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2scntjeki.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2scfmblkf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiehplc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgnmiss.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2empxlfvx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjakftq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwkqpvh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2abjhwxzz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfheudft.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2opygeabw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hdugkbsf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qxicvkph.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2linfnmmw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmyghoy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsjfjyu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcfspmu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwvuqhs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqxyjrb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2psvubmeg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zctqtrdp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tkubuemm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgfxppk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fauqktww.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmxowcd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2skrvjzlw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoxmwla.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcvwuds.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2htarbsuv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfpojxh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdkufzk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbngxhg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oohqhcks.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bhebwlqm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrljcux.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2baejkzzi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2czuioqsd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2icylpnhg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyokotnw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmondtl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mffiyjzm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxsrzqr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaxicha.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zelqwwhk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkqjnai.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2twsywdyi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvokfr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzbcawt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swoihxgn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrebbah.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kypxrcxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvllhgxj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjtcmfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knchbdvn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ceceebcq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqcnwvx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mobwfhyz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvpjbbj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2doefkrng.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zprpgelf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eipwxlnq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfwktrm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hosefyku.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2thyuxzup.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwozimyh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbpqzvs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rfimrrxy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2trumnaja.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuvmuxt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ititygge.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzvubka.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kscpsayd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fpelgggw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jozgirxw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpepbdk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yppcinui.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eupznxcc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvipsvzo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lanhzbsn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxfqzbm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2esdibrry.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nafgcash.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jygfxivn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmzvrpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeudeav.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmmgymx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2btkkknnc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2skcsiskh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eecdsvzj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qonrknhw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcvxpee.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpqevpn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2axtlwdfo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuqrdlg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vucviiie.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nqldcfax.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaakejv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bedpycvf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2stdihvda.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnzzcbl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbcdwgq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pupppnhr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnsatrc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsmnrlq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgogvxut.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2irkkngza.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmhxavl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyjqdwg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijridmqb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xofrnska.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdqokpa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzgqeqj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oesnymym.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkdddwp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyafsjrh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wdleomyh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbxneno.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2toqcpxzy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mjilydzb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rpspwiad.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhiqpga.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huhmducx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cldhlfbd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjjruzh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tfltvrvm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qenrgdei.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhxeupw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tissnouh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbfryln.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfeixki.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mljsnfim.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bysvvkjg.html


<!-- 参考信息 -->