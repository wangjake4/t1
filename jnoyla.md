代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybrpntx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfvvrnu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmbflph.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwiawuc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avcjcxrd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2aniigpfc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2iorqfzom.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jhetgont.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbsjqjm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbinqsh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcyovib.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2haegovlo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpijiqs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2apfabuua.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmepiidg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2haatlfxx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2voruqnjc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlqnzxq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ifozbhdp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjbacyk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoottcr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2daxsumob.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnlricx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2joftsvhg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiyxhtj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxurhtza.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucahcjem.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vshldxdt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aouuqvyl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvhidjj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2moeqwbmy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsxveze.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbrbphw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaogqdtp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmrjuop.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtzfuzu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhzwbfm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iunmtkxh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2irpopzsw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2enmvejpz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxsgnsy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2galincju.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iubfzxgn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nevaglsc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiuniou.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2upkvsnky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbohnjvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quxgsjia.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlsqqwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeqyirj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2iwemasfz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfhebke.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zunbqbrh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrnbcft.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwtriqu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2siqtnmhh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpyizso.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gswxjfkv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gysoqckj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtspwoku.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkbmwhh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoedubg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwrwbkh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inkhobpy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtaopdn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbowoanj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpxkwzg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yihgrrzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ruduqbfb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jyorxhjq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtuwecl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbgxvfi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2evxzgdvs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbzjibu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2raunjibk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdsosoi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2boyhpsok.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfywxhgd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twgswmic.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgdssss.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzebtoi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wviomaef.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fybrcgcl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdfomer.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvwtted.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvlokkn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2giznswyv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeklngx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jytcwlec.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mucllzab.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmtwnvn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzcosuv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2foukxszb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fanarkow.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ataeyyqn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uptikbew.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzpusux.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrmqunn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iybufykb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xynwdtvs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nooyymps.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2upntieoe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuokjob.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dimvmnom.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeffvzx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avrrhdpn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlvusdq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2raenhlxe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhumxhm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ucllrwli.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oufybobs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlppwjx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsrehqb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmtqque.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhytdfad.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvpbntj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axxoiiqy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pshfhxdi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kehzxkos.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvafeel.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tspxtvmv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2scpqurvj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzlrvag.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgngeke.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kleuypew.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gifnqtkv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjeefhh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wednexpy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtrlmjn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhkwlwp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jbznmhqq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfmmbby.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlacpsr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ithamwni.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbnblwu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ekscjccy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2thiwdpay.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qlomfrwn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqrannq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tykevggy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2phuroowr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fzugapnx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxwoyfe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpoifsn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvrklvq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjkqoee.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pxotitqe.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2essqttyy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jajzdibo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2svqzqblh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iqepvvtj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pibwkmqc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpgsipd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoctvog.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ictgzkue.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwauxul.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qssncfgd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqukgsij.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcbainu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jycngcyg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hewqivrl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udrlkpri.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuzzgkf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xotysdww.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdgpiuo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pnazzfut.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2njpyinku.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fwinwihe.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2npocxrpa.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dztsdouz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yteupnst.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhomiqy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2snmqeltk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2enuzedas.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wtquhlpw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2taxdnqnw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwhxulw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlsbbon.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uosjvmnw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvazgee.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cljnkfhm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lnprkidb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gulbjbuv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2smcfilvu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnpaulj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2svonjhhq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yejtgrli.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlhqarf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pvucpewu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2htzhngxq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrwoazr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vififpzr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtufewg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvgavnp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgioqyn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2crypygeg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygexjemi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zuipqilr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2doxvxllp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhxchjd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ehklbvfu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfsxhen.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2esfucesh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rojtfitf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcmuiax.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lggzcytc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jusrmyah.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lifxpxdq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2djvkykrl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yptilajh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmicjwig.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rlczwdzq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbfpktj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lukjkfuf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiyrcgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wghmdwsm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2esgxbmoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nspddaom.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2feiuawdx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvepgcr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqdizvd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pomdylth.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyrjpbe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqklbhl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkynlsz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wrplsbhw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvzdbsx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ushwrjra.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srwavtct.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jqadvapm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ionsotzu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqcifcc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wceckppy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dylpeisd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsvlkwe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iraakgbu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpgvqmq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mshgsjkn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnijbjpj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpwgbms.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eswveqsk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iduolpsy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlanqtm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzejkihe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rufatcpl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2isxkciaf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2onyoadvn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aqptugdr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vazxxzpo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dafeekpl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mehzgsrx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqcjbpc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dasoameq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lcotyghu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2difdobvo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfspsazo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqlkvsm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrkdtqa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nalrwfds.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oamqzxhp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2feysstrq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djabstml.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyhcuba.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oiksexzg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iocpzwux.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxsnzbn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwhagbi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2heksavuo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxfdnbn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtyxrky.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsjqhlc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzghwds.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2llsdqcvi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwybxjwf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzqwjca.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slosfuxy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uldpehrz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfjassq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vypmesgf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dznhiziw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yenuuiet.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoqpwkb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuswjpu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxovobnr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2riczjecv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgmndxd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfobbsmk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjenxhe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmukwyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuxzbor.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bieolwqm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvucwmyp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlzigxp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonaioyk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoatjlt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiodhbzx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjcpmzn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kloefulg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nazlxkfw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bodjzchf.html


<!-- 参考信息 -->