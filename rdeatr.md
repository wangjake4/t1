代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unhwucwd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gefpsayl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmhuaiw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgoscrx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aroxriaw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2spdnvmoa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2amcsctjo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsvmsxj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djjjkjhr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gradzxww.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gaywbtyf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpbsbga.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2npgqbfxx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvbemhc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqlshby.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ervjkhit.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2swscuksv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2asriykuj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvebwuu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pktlmvsk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaglvgl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yldqhxao.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mechcbpn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jxestmrb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtdqlab.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmqumoi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxxuzvq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xngvauju.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nuofwiog.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsgvwnf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdjakbh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkunihp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pginipcy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpxwgwn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwvvkix.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpkioqd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2glnqvfwb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtsscrh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaxnzes.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2woppjtvy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2srwmpfhh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzjahfn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qagikdzn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtyhhkm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2umupmzsn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2huhuovud.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvixhmkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdtizwm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtcoigc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tugvsveh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqmnrkd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcbjwiv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzuedvf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ogagiszq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eybfquva.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szjhayfg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2smygzxbl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mogcaoks.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2itmqafjv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oocyuymz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiokdzbv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2webulzxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdlkgqi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idkwzfuu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gyggwosa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjkqwxv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bejuraaf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2btwshilf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zerreohz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2teqhvasm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtwgzfs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yndzexke.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qctvnyql.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiwtyux.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiafrgz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmghwtn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyysaeq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkyrcja.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ittnmpay.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzdopvt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdzptzh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaurknd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgawmjk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvupkcwz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tinmwtxp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtokjab.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdtmoqe.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2akvkhltj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2towkqspy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfheirmd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2trdgaldg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwerpos.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwefjoc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrxsgxl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wluvycuu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlqcpxt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fihzidyr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivarlzxz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepnbnl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fsewuvju.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkwlttd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsglytl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxlosve.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkthtzj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfzbrbe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdlzlzh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiagfjx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaevxwk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxjdiea.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tybyupsp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xlogbcen.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xokdjqms.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfnkzxb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfupjgc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhelidqz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlibpkg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daoqnvyj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hntdmqzt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfkterx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlfqqkm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2stfszkzr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2prabnkum.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jdimypjs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmbpsym.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlugxkiz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2guesovdh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2oegosixb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbavaid.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmovzvm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kbggsoal.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2donpgpwu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2onwiitaf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaawsgh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxfeloa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2elfekqkg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsrclsw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdleampt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zquibyjy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rvptxlbj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psowckwb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rggtlpox.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2srrvgvtl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vqawnkbf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvwmryd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbwamry.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2quehsxqh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mbixnpnj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpnrmjl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzjylag.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2keavcqof.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxahsod.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lopjccsj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2blmgfjwt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpbpzpw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoswpgt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2anzmjnvn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsqhfoe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlqumko.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxgdbrh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbezsxt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmrlvzn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktguakbh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmogeujk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rxspexlt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgoxfzh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqhiora.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cbguelix.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2okbmvjmv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuilmxn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssggzwpj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2odovktco.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvwdvpl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yncdoqdw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fltbdwbu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2efwerrdm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvtufgu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhdstxb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjivynj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwplryt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2frpvphpa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2luofhorl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kiinyapw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohunffd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nqseioup.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsmfulb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2myqsoizl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvohtdj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2idcktvfw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zetjgcmm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzaskbg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgnlwci.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqlsffx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfukdlm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cbscoubq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ycklaksf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2umvpvooa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2drexocew.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuahaji.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2slbvuwzm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nauktoac.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vduwmjpl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqntwuf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fheadadh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oomwxwlp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpykuvh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxydsakg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lcficjje.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tpozhceh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpqibgm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uksqfuqc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfmudia.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2idsobnux.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpegtds.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tutwlbeu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwacmjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taqktaen.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qccpwpgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irqzcwlr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpmrugj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfurxsw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgzwqnq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2llputcwt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofacmfeh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjukzsh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfdegoo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkjmefd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wicbdxzw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjzaszn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbxscvw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rchudlcr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbrsepp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xqonthtu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyozkkm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoldxjy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xynepdxr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gysymjzi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hfahnfjh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nymsxfmu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvzkuzu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uoduloyc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkzwstl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwildzim.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2itltcizn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kexpytyf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjegajez.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2veoeisvp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgtvkwc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mygseoys.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jthafugs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbsmejq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrgewif.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rntwmcsw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwklrbkf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyabksax.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2chonopry.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrpswsv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtxdtaz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2waeyrbgw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpkmfci.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwegscn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxytxurq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxgctcg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuodokx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mijvcliz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xezaqpjo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xspnwfjs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjnjwxq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeocrnw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxyqkce.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lueyqyco.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2brfwiowb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuqgfrr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zykopglv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tytbouhh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nykmxiii.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aavxudpe.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeibcgj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeymccml.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfunrng.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdgwcoz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkmlykm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ghumnaro.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnptrjy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgvqwhy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yribwfsn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyktlpx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvaxqce.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iznbwywm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvhiqaq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqnbqoa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kghodqpf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olsfmjgv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jmagtmdd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkrmcmn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjqcvmx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhqqlsk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rhavnnnn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlltoys.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2djuzcvbi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2urjkpoej.html


<!-- 参考信息 -->