代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvchbyo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsavzgo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gihpactn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyjoupu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtyiwef.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usuzstkx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lzriyghy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtmegfy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrbxaad.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2amxdbvqz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhhvurc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrrpuoz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfstqvl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyzjmvq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmfkpei.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2haaidyso.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bccbxdcn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsanuhnf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2quldllny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blvjqbye.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrrexug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvqfgwg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzmujco.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxkccfe.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdrbynq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uspaoamw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeiorqp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oznwyhig.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2clgczest.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiyudrq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcqonxj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2erzzdkui.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvlxwbl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jazrmqgc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkjhhnr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpvkpeh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsoyopv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utlhyles.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcuqzvp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcbpvqp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwbquvl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwfgmf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yidmjibt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kfftxgaa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgrrlrn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwvcnkg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2msifhpxn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2brhnaauj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xpngholx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwwdywo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aitlbwdn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ibekmzva.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ogupeljo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iacqjikz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ooemhxoq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffumcxcw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adftfthh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpepxoc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzzvsrn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiojnfa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaoxmvb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsfynqb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgjohfs.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vdartpfk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxromim.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wogowfvj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2frujteue.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtgukht.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmovmgkn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvqtpij.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxwmwbo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tajeocyl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhdcieo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jeegzrbi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qusgdhlj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gutphnnz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnaqgzy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkxooqj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ballakue.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hhexcbls.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmdizyn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uyevtufb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ktofuszg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lupdxuif.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnruvxqs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2watrntsl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuvkztf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eimombzi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhehclg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2daysngsx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciammiaa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2czczbiqf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmgudwp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmnhglg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2chrcdyvc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2btqgjqjn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyjgflk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxmjwho.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2slzfjauv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aogrkjci.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gogyxfam.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2unldohyd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mmttmasb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwpfnhl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ellkneah.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiawntv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wqayzxne.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uiodfpsz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpultrc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vxusbppl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vravsscb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxwmsrt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2miacilbg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcmrqds.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2akguhuso.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2akgtryws.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ruilhwkn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpifozm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbhzcpm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqgjoax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xyezwgrr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbxyilp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjprgveb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwhsbqf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzewwyx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2efjhvvre.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2levfsjrm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cituwwmr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2imfiscua.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2srochjia.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwpnmqx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ltigxlzx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkxarku.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blptwtea.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wromymur.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxsexii.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxyvgxo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hoewoncd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2elbzkmzz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qaylklcm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmgamwi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhauqxeh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sasnlhht.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gqshklip.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jvagnois.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rebfeydc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qlymsizl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2praqrukq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jfienmju.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrllfud.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjbjhbl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pragjwvq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiluvfl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgczbhl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2btucqjwn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ammqxmvz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiwahgy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeyzdmc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2exfqevaa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpcwjoa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ekftpvrp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vhthmacc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuqkapx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmovpcwk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzfcafh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2winhsoik.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhgwbbq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbwpesl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjbndmp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nifiuafx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eezhtkki.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2coqwodzz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2stwzqlxd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iltfwlcv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dllchcbw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuvsois.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjnpplw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juoyyhjb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bunvedzb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcwjfug.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmatxfw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2paqduqiw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efoigndb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfbwvhx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpkqjel.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzwoodc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gisuisjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjetbchk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeefwje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtxqarq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkviqcq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpwwuoz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gompmtav.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iipvwbuu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyumdcy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoighgc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2popdlvyx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fsijbrbj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wusbwfva.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vykjvaqz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkvdffh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtfywhi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjdujyx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2deemzvjr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgzdxam.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lozjjxck.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2erophlbx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2waqasinx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zeugxmnr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxoytwk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcdxcyc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwccscuv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uygrlpvm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpwzsbd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2akkpxmcx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjbzish.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvqncgz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgdheoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dleqglum.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2igbxllby.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrzrwhg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fykxevxr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rqydorml.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nsieigyc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkxtvra.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgabpyvc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnanpnew.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dihxxkhg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnykzkhj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2slkpjbfp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqbzmys.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zdttldud.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrjguct.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcyfrnl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2obvoiqrn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2noylshor.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2enwrfpjk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yggrlrju.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2unnnraaj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2belzncle.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sutdsciz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkfjnna.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbwpflr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiewstl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlytgnvb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxwgqze.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdjkowy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjagvlda.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lweulgrn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyqgqmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2itddzfsn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbzezou.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2osqvpqrw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bsawqfep.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbnacdj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rocljtvp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2snidqtjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxgrgnb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmulbba.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcehhrh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpfgbfb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsgjxpx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzuoxiu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqliuttj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nvolxmud.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwybrsae.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ewepdvey.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yczwwfzb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zinlkvvn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzblmzkt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ponaqtqs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2utldhvua.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2makgtdex.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iizlqbig.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbhwtbl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhkhimf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqqtbih.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2culmnvsc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsxpcza.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2beqwfrsm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2czyqlmct.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgwathz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkcauly.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnaypvr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfgifny.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gielflfq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhaoumx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otbrrkbm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsakawr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohguikiv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdepagop.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwollvl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaetjkc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zngtydgr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjzxtfz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jcslrfye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhelwac.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqzevad.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrspmau.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzjxnsj.html


<!-- 参考信息 -->