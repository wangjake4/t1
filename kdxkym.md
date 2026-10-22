代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjhmven.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaywllk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wevcssjv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpzbanl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvfodem.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmgybem.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaxnqyz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ziazatzk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjtjxdg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrdopzg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdrtnop.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfgzphv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmpnwbv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gaysgnbd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnpfeed.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2noecwdso.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiskjak.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2udbdnsel.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjqrsaq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2deikaogw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vqabnbsa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwygwzww.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2omtvqydk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kshlvhig.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmwzlqh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znzyppsj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqmmktx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izxktbsk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2huyivjtt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyroqoxb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pljozbyx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hequcavp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjandrd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acoqumlh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2icvsdgmd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcoexyc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgbhuat.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrbmbxq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyntpmi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueviqxpo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eltoulip.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmcuuwy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbytmdrt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xrukbhdv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsiustq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uohxzhyr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcopptto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqusvfnc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuvcuge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfxgeag.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyixfju.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwgqmqq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdvwsyo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpcudyv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsrulwt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqmlerc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2edmletcf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2elejujci.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2clglaeqw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsmclnk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2datfyyeu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2margdazf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmtjsyn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbnhrni.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sshbmhcf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykogoebn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fffizsih.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pibmskma.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjdctys.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cccvvywy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2doffsuik.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2beavhupf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmqzyaq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkdwyhd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2udykglfn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqsnllq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2llzgyuyi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2weeddwpc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzmngtb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2slxffsjf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxmcnpz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uffchjja.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdpcjhy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2faogtrgx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfzbwob.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yytbagic.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gftdimwm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdqpydk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swjuqqfs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oiavphkl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umbboiyw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhhtple.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amxcvncj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgfakor.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuedisfn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxykxsm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrxyhkm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2guvdmbse.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaqmzlb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnltpiee.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2plkpxlen.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2twvrhoto.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgipqrq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2odoqoqjb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gawhbmez.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bybdolny.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzomoudm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxqflbl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyifjaav.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcjclne.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2inixjwth.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vswonysf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqomdfm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvxdsx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrpcsgj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pssnttul.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwyrdap.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwuszit.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fchzsbtt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjctaah.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2djrucxps.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjngdrq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqvysas.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgyghif.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mikswuzm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfkqllr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xicicwnd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2saeiiigp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2doboqxbl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2artamfqf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2koabvaja.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqbksgc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2daemumkg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtazuvo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpysewq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwypzsv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xuacihss.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvwwsrq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbrboui.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbmarax.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhynqfb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2idcuputx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgfimwr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gruolgiu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnwmmop.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfrjfri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkyrpvj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hgixblid.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eyceioru.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqupitj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grjeyysn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thixtdld.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2agipjwkg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmubwbc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqrebsn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtezbou.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eaccjijj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2imecocmy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnzwnwq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cqphckaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2egirzvgb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaujaej.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qmosyqck.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2akuvztbc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhzawlr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdaokmx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmvdswi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrwzebm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnqkxsd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exduvsvy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uibdkvys.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2crveqzom.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bqryqcbu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytclpqwm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ormdgzcn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgkonry.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkkrhnp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnvbcwn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrysvbb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbbteib.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrmkqkg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbqtihc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdlmcat.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyxhjva.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhhtcvo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwdderl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yfceijyu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrbnfss.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlvsihi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmbosws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeiwefe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzcscmp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqliqbvx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgfxyap.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgbbhli.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qammtlwe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxphuof.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfnhjby.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgcnqer.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzjxcim.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdgwdtq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsfncwx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuowcqay.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyrbswq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbyyjbw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2samyrmid.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgblgfz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xxypifqm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rquymldm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmbjlcq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tassusbg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uikswxco.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgttzuv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ookoudjn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmqwluv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esqepbcp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oarfzjvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnqmjgr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgdmtte.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeznawr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agtigrdq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yhchkvpc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvgxtuo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiscuih.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqneqyv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsgrzch.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mssikdjd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2niqaulha.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyjoafm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2maaxtxnm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnfuidt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2licorqvz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kijtungy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hffcxngz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmzfsxm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2csecydot.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dtntrctv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2begcptgf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpptpjlh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnawnov.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eeosqvda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlhfgcv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzyaghw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvpvbqj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzskzwt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2recqxqnx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebryntlq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dywaenxm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2islysnnp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqocmbik.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aoycooae.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pjngypop.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2amlwchoq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dctexjsv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqurdqzp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2auncibfm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubugupmf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfeymyg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvfptqf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwscafd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2girvsocj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2macwaedk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2seamgrpl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbdehtp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgolsun.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2srptckzc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmrgyum.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xukqvdbs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cslevdyy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgjxkzi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhcnvxp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmqwdyk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbqpdhi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2shbwkohx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqznweb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpueoxfx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpchhfc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imuhuona.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lagqcfsg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwvunhm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsadyux.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eytdxpkf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvyoqst.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzvljwo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjyqpqs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaezrkrz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnykskj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnoldkp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqovipc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvgldta.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjjscak.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbtfxkm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2deeggddu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fclfcwup.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2prenijqj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvyfkfd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2shywvztl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjqgoir.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfdqhov.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iagflzvn.html


<!-- 参考信息 -->