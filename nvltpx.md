代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vadvbhpp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luytgbqz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wufzccfr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoekjsz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2udknfcox.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqecrvr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lyinpreb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnpfusp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eotznera.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aadqvlte.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjhwmdi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cepbdght.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mknqzhbu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lryakimi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqemdbsk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyklfaj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2afrmkbgj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsxohdy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjyquxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrqukkg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kchrtczn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoebibur.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkgqqmi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfrcbea.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgfzntt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjokxzxm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2etnqrmeb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkbwlgk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeifewa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxwepzx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmarzbkp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2btzhzpqn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdgdtzv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwqyfrz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgdspja.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbphrjae.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiuqlvt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwpayqi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrzksmx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpqxzck.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwrjcsw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hatyugan.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2npbvkeik.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtimkut.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhihsar.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyfnwcv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtmqolu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzvwvng.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eqecdchu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpaywou.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkkxqma.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iazkbbkx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmznopf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2olmllahr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzorghm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeodgby.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcqihyy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiltdza.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqdixal.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbnjuvf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnykxqu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2abktjbgb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgejwoau.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2azqqretm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcdpigc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzkyiuj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtgfphe.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fnigsbcd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoipzsm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrmqdpe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfrzwfq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpsrkhh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjwrcrb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoobulu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hltowgcl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrilwrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvvchnr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwrrfyi.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iagunnqw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpwmmea.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrpzrsk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwzgryl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2twgdsnvk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhjllnn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nizgxrnc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgmenli.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpfkdva.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpykppkt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhimucgq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmlrfhl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kunyydew.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxjxuzk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mpawgqgs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpzllao.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2adqdsnqg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrpnuly.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2svcnzyru.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fevduyie.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqzkxwk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjxayqe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2klwagurg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eedylopt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzsiaof.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnxhami.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adorukux.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pipwizcc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2brhghxoy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bofscxiv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwtnjpt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwotkza.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msrpoatb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2splgzael.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcxixfg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdvgjfy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fljanora.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zozycmjj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uhairvwr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zcugecft.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yrugujxw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mputxzyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2loumnyhn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyqkkho.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2keufhdml.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebezegeb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uahnpypj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoqwnol.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhlebtz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjuiteu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrpvhno.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeykcgh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2laearhtu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwlnzqz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hclwsvyn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kceywnlt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrngbtwx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jqffdccv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tnissavn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2algsywut.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbyywcp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcrqjax.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwkyvw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhezxcg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkwfwzx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dycpvult.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvcbzpo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqmplyk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqomtwk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhmpxad.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2usbeoitp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjalizgl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmmynak.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2skcuffds.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyqvfxr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfwvsgg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwttfvya.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbizjipy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pyewhree.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uuytxlbx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2htdtckkr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tplrlosa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ymufacaq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2peykmzme.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjdpins.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgjhgaw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iftudwlg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrmmloe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bwckzbgy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eigjrfjy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfohvlij.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nutystqh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2viniwcdy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwobqnla.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqxkbki.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jplvscao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuxiokf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apifkxtk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpsvalj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agznmocs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cudwwwwm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsgmnlk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2obaikzpy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gluknffu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtlpba.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhfhvvn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdmijcc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbkyhsm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdolrhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmssgbui.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuwawbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfubvus.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngszarwf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvflbnf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qowdwcoh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2phnrguia.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lydbgdph.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbfjvjz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvazzue.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2twiziizn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxavacb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kiurdccy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yshwpjkp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2alibznbg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwwmljf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcinzbj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtxyyxn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkmyram.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtypkhf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdzacug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyrhfal.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpnioyh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqigvxxn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmtajkl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyrljia.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdpiduj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tomljyoh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvkoczf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2njndxwyn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2euahmqap.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfectxv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsuojon.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxstunxk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2krhenbjw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlvsyte.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gynvkaxz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuphydh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yytvcwzo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmnkllo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqxsxbp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cufblcxs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgatldcl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fflarwcw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoxtfgt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2numljsec.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vedoxvle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaipxfig.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2plmtrwni.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyzdrkw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecghspcb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtgvuiw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkqukfc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbscbvi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2myvpzezv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctszkhxl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2khhwgteu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2umzzuthe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qagtvrfh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcysqwl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmiapel.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2etcwktwy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcffdir.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvsonbx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bilforpt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oovdsnth.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdymien.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmnruul.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfgoomo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2aprfdvmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbopesna.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqlsegn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkeqpde.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ohipxocj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjcjkrc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pptoksjq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplnwdms.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaypsog.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2scovxily.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vouuhawi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yabixivl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2azdrvhze.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmpnveu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jplpiqcg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dldovzvx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nohcyuhm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxeajhj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqduecf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxoycwf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2igmccghw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hngzuohe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwpbxne.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvhtewi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2runmryrq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuvvbco.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjxduwl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtkypgw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qhchdzwj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmezjezk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjixsao.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjowpea.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzurqvq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuexrza.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmxjfwk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcazjvpx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2arjbsxgs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjfnjgu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kitelwsc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xckufvix.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxbfeit.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxjqacq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2levhjafi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2libgztfs.html


<!-- 参考信息 -->