代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhuttbi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mfohaxtc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2atzinlds.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvmanea.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phpslbif.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lkunfbld.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gstjwgcu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2graolyva.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chlbavpf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pydsppbd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2crzelvll.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qppopiil.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2neanuqru.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeovtfq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjqdkiv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiqwskn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxfxljf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnqxims.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fvozofoj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2glbkotop.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2izafbkkp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2klxxjgln.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2djinvlxh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lddfxwxq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2stqwvmau.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pruvwgrg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbccqjal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuqtjhk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnnffyx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkapqvws.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxgkpsa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kixuifyb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqnidyl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvxaywq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmzjuqc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpylmkog.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqpoiyi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjkurfb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbszowon.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcfrejr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fieqamis.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcsfoaf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dedqnrxm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrehmxy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2biocnxuy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2eiefaltw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrfhgqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2salymkbe.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwbvmaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glplkhgq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsbpeol.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cemckqhq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2besvjupy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gehckysw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mateatnj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnxysyw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yhimumge.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hilbejod.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxutgipp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwtwfda.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzhawut.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxegnduv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfymrys.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rciysqvf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgislef.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjhoqnp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcwwpiu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhalbgk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqghykj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqhhazz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2frxgbesu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aqignspq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrliinf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpgzdxx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2seswnnrk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cltswqps.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bogjqgnd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtvyjao.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvnzfuu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoilapq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2malaebhh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yleatvan.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qctawikf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drgwemld.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2twnqqvpx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oumewwjz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agffnpch.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqgzuzo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcowweg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2icesdieq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbszedlb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2klbugqdv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrzgzcz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoifbjv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeilwvbo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uawjfrzy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzffddns.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwdhymw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiapdzu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvljghlh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zatfrdid.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsvegbs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gizmtsdi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvnqudu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khscwpwp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbfzvne.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpavmnqt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2szndqzns.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsndfjn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pkakauqv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsfahdi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmwazwx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvdnjbv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvqbsgx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxkjafj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tktcqtdg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yddhorha.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2leedeqcb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tozcvtcv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2shiohdns.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzhctdp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gofmqgwg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbrgwab.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ircthezs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2aysbeuxw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpadhhd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2spsaqvfa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khwfojcz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcawkzay.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2aojdwtgj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkpicsx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2saoboyuc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wssgbvgd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmzsyis.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uuglundj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2miwloskq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kljpspbz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bdioswyd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fduraxfd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgotkzgi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jswfyrcg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoqwlie.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wispznea.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdmjydj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyljwfz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bsumscyk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qteqvihf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlowizb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzangzb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbmijix.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxcwdkl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpqwtwb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmctfcs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vhigduaz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcoolxm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgwtebw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbvtusz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kknnanja.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgckkemp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcmcvyr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zhentphg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhugygs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjhcrub.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kifzibod.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2eylscaqq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hmctyint.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cglmgwyg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhteeyp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gthhjwpw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxdomai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgovhqc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrrpvwy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwnujvx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iubryxua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmhdezf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqvfoid.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2atboxrwz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hltqlhex.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rheveywy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zutwfhzp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnwhfpp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sbahoayn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvyghcq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqporca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnvpsv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdelnds.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtoysfk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bojqagen.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hejhlxzz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrazwxzt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvhvbsd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcriiqv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyqezdc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2igvgqdjy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrjrcix.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sogbcgqi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2czcdqyse.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfupptt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcmhzor.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsfjeqw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvbiwxi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2djspruln.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uldosdti.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdanwajk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqereup.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqziqds.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2edfolrik.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdmrsm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kayrbtjd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfjzxle.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzlvyfk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jhupzerl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzapwjtd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnfmrxu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cokpdyvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anmfvghz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yultdbrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiajavf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhosymw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fsytwteu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gprfhxdp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2idkpkfgf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvojwja.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwennij.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2alibxrjq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkbsakq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhmxmji.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvdzctw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xinixifc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2abbwgwad.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyohhfi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgeolwn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2twflnyfr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2emkvcsnv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2avzacwxh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2edsvufnc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwhapzu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2somxiklt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmopjimc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aonjpnjg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qukxpycd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtbvwmi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfpwogg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziosrsji.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvjbxna.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvwccxr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynachvxl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpnpciq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfutwlj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwcxwmc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgkddne.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xtylnzzl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jplvogyj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqgsjbd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2edtmdnhy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jilrwxgo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bohqnjvd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2axnjkviu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdrmfrd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkeicdi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xslytmlr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oukrctzv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzuuzvf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsegaxt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghibdgzm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvxwtts.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcawiae.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2irxrsxar.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdzovrm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxelrzo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2plsylffl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhxokuc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2snzonlnq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cndeslhm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gunasopg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkzdgrc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2akkryosq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbdizua.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjrwrzo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrnfkzq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpseewm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrhdgqm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpszwhh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnirvar.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2weaftwqh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trvxhesn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcebfylk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2incgucwe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rgabswry.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrftoal.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kobryltm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmodcpsi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tbclxgva.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlivocxe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zozuxwth.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuyqlkl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vnozsdlp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpdwrfo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrhrikx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpgtktj.html


<!-- 参考信息 -->