代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwrhsfc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlijohk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbvjeqe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vpspfvsq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgxrmqs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vylzktpu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spjuwcim.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzunzzq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cpldpiyy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhylpyh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcqbpwl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ryorgonv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqjpozd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqhokgb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqflpog.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2inzxwgpv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2znhltzfv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhiqoxc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iavfdxlz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcotkjoj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsmgllp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtpabpd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruphtawk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzjeqvn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2djvotyzq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2decbjyml.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvvayuz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpzsltn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqgmdoi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2onuozjqt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2owpiijtc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tusinwwz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxjbjmv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fawcarsp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmlxjru.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwumdqjk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjsoqjx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuxzizz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaauqxzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mctibwkm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcmqvjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evekkxob.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiauwyh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvywrek.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qljahugv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaeazzr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmyocjt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebslwyds.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyhvfsd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2daszgadr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mreakzmk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwslvehk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoxlxqm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbywvyx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zroqtugj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqqhswf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oppgnchp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uepexhbn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkkfieg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxbhgbe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tltexjoz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vaonyatk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gzegueci.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrccrzf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2igsadrit.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxntzluy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lapgpmub.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiuwjnb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2evirruoa.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbdxoda.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yckepezv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdmwiyh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeqbwbm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kfntmbtp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqavdoxq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvkqgyx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmftzlf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxuomgz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzygemkv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fuctsnav.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssthaczw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sihqzbro.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnjvqce.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtsxdfh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwifvvt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaankynp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcetwqe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2enbpumkw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nflnzzxb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmgcwnv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sszozmwh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aaayekak.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfmmjpy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2raassaha.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bemiwcgb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pucnmgij.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjtiqkt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrowklj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2awswdwqx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2udqjdjah.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgbjqqw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kkozsnkj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ernvkoln.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxvljqs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2knmzwlcx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2csytekgw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2minxenlc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aneqewyp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzogyjm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2slxudptj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbjeveu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eilfnlau.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdsfuld.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cviokpji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdnzwop.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fcftnxxc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsrqfoo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2raqeyxjk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jujasmrt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icoshayq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfajhvu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mixvytqk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2upupwubi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pufvphwk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2whbkwjvu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxijdmbd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfzytur.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyjlvku.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbxemrg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oprtnwfl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2custoeou.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgimndb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhxgpun.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2usmkhwfm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkgnjsg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnnijcz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mejalkzg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ndspbbke.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hiarewvd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsmsaop.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgdssre.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvgfgvg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoqkjgv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkhxldc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pifmjkjq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxwvpvi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkekspvv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oikzevds.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2guxasijv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwmtlvc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2folkhdue.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxmzqqr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuzyoee.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsjlpnz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znrjdrwk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vshvenoa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqrlnel.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2crhrbgvg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uhshoyue.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxrjpzo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwtmsso.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxplmshk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsrsusc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrjoskq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzoxzxj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfxchfx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2usmtcluy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2piyxlxmu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiiyemx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkumnzs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bnorsrjc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2blyypkyz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2noxjypnq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dvenqrce.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pljwmtkm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnizols.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2finvjibe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aahopykd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yymjmggh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2efefcsfv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbjwrlm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvohpfb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnfndpd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzkpkfm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lclnjzez.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhjbpzo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tmynedzl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbdzrrs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2udknaadh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvoatqq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgggici.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2srvdanms.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2monzsdew.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yztejjov.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fbipxgym.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkiyfsz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2usiftsgi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kammvfhr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2inowiqwz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xslsvsbt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2shwrgdzm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2znwvkxgy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmvwlhb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2przjgcyd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnxbibw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtplwvd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2biabigzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhprdsmx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvlqxia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjyhulk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrgrwrn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpiriei.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmgnpof.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtowqai.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyjeixq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bftimaog.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzyjluf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wenyjtop.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqxkfsu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cukubuhn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwovgka.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tnczjuch.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoxhftd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jsedeauh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwileghi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhbagft.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqgqgfx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtxwapf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tytjjsoo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2afmepmqi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuzoyxi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrwbwkt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bewzocsf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzhwoqn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhrctbv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mogfoqxl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffapngjj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgpnnhl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyasbauq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lavdesdu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzmeuiv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlowfwyw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjdhkjn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2svhuoqpk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuldfom.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2krjrigyh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxisxbhh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aayyfyde.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwscawva.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oeusfqiy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrnytcr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cwepoqcr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpztvglp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoxnamr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2duizkpfd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiukgag.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vycuvlon.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsayfzkh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwkyqcv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrldwbo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkzqatw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fviqaqja.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdnajxz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2epdpeuou.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpbfdpn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoqczic.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uktglhgq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrhamor.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjjfesv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uogaxedt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2arsldngb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfnygcz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvsllyp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ruchoupv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2shyukcer.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbmbkxq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmsbkiq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqrbwbs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uulgnqgh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jssmjkrj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xttlgyrx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsgsufa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtomybk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etxiepie.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdxfulk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfglxvgt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxqygym.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxcpgrr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fowlpcth.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2esorrvua.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbgkzly.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdrjgre.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcmzodi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gscbvmwg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2stdlennw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2apxjiues.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uprpgbzh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyqifbz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkttryzo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoxtgaz.html


<!-- 参考信息 -->