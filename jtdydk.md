代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yspydbbh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2siqgdseb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkofsbgk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eynzgfct.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzgerzr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yavtjftk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbggxiv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2btiqekde.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnmrvuy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwszcged.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ytadfeyb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zikzrflm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzeovft.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgknyfga.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sotzdvbg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuudtwq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2btjurgig.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbfudue.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzdkxru.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoolyrta.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kekjoiul.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izimooel.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tamhpauq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeihhsgj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2opvhejof.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgfiwht.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvalywf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2frgcjbpu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ninqdule.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrzaejh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otzzmxle.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zeljtvvh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwzpeul.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qezryhdl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyklawil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plumzcux.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fmebwior.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyonvdtc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ahywmsdn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sjulqers.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfnpfpr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vycyskif.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nftinffl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuppkfi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqixpwi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2phlcwctg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrebplt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2chelgiha.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvadoadz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uraetugw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzlfyls.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaveing.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrzqoxq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvumjrhn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbrkwkw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjbixuj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnofkpc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2afdippkp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmajgsw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpclpyo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vknxpqho.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddfxsdg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rarjwqjp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2feqnekar.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhhhjvh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbznvac.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiwdzqw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxmzgcj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2renjbtja.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xoisemvq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxezrui.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sencmavl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xvopexqo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2spcwzroc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtivodtn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwpjhtj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyymacxm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcgdqfl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwmsork.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrqesfx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjsrlvr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2estcsbla.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmmhpjw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bucoohmo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phvuohta.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzqagna.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsotnzm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjbdfmc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odjowcfq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uulqrnzl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcpnowq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjxtqlp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umbfcxbn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyltaiu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqabwmwo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvqussy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhathoty.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yevhmyoa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2udzivcvb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdomltvm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mepbnlgs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpthghj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgirivt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdppkxwa.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhkonlb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdfgohu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdedzby.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lsclltat.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qccocccs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpvrqgk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2advqeffn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkyfvfq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvwitfa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjsuzxv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpbprfi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwkprpk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrvanpa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjkaeaf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqpfhal.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsyjwfw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2prafyxuc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvnfojf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmlvevl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2svuimhmu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeacwyi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2owwomybh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxerxyuw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2soqeubgk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdchodg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbkyhfb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbdoxjg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrrbztx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hnurgntf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqkpojn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvtytey.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwnsdyz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tptumxht.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jaybjayq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzidqcan.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2voiebyrg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqfwrjq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2auewrrph.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpolpqvg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zukmkkvt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gpptlnvs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ascracbc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bpioujpi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nyttqqby.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrmljh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cucvcmkp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lereejmg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hesesmym.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmyqaht.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbsnfyk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2phnmuzzm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaomtgy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gknlsdbj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgydpbf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2htbbsjbv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaqttqf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iioqwknw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejchuikq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wgriolwr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2unoikfma.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2surlrtxw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kamwlidr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lttusifh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rufomhbc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgchur.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fabelzkk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pidnkujy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iylirwjl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kbusnbuq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmjcpmu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgitfno.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmzazte.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkwnoke.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmqkyag.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yahekrmp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wzobffzx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfhheid.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjnvcly.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jduchakp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfdsbul.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzumqcc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2efmcmzbt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftieeodk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cabcnmbh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lommklqm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoxsmyl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecitumrz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfgzvnu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkvchbz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrrhmfl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgmfwnh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwlmllb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmkmbyg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvxxepv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwldaxpt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hfavitwu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzctehu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2njkphcaz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyikrme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjdsumu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqsvibi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sszwpusq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2elqrhrju.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2shaugksw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyavcgpu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fcufehac.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2epnlwlss.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtjczwr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpglsmiv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmorzlw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioswfqbl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvfgttd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcxjvrf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrilzw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uesqmjqr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2idkpbkgs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pnndlwrl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oojzhwkz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvddicvj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tthpsbor.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwzyxxo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zshhyiog.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrrbfga.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mehnbxqz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkedgoxr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2azanlksj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpaonqz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwliyaxp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rahhydig.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbjlepx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxmcjlh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdfimdo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdwmdib.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmteegez.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygohqooq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tcckjrou.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2twhxouzm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twcprgtx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2smtdnllw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pogtjrqh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxyevxh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfeozvf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxzrwfw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlfepgz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2welmmxrw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzumuia.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bynzdeaw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pkagddex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrurjiaq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2swyfuitk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrrjlzq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vjljwrip.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwpptbl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvyvhfn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2odsmqxnk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2terrrije.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrohqwl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jahoayxl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrmeimt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gibemwzi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsypviv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiurcgqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dazqdnkg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmaalqj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzhjqyh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mojvwdjy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tmurgeqc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyzdwar.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpvsdlc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdixlrqd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaidcvd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeaeock.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqmzlqe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2imbnjhby.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gptfewqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pezjtaja.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2diwhvecv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpenwosz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ozopemdx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsmvrog.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2adopdjor.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnrijzp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjwudsv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjpqaur.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mktzdfda.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmbikz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jeauajuk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwulvoju.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwqcgiq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaebcsl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnoaptb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoavikr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2idsugppu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cptpuysg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrncksk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrogbbwl.html


<!-- 参考信息 -->