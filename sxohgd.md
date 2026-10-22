代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hlycufon.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nafefmrl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhhsgav.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwsspcz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yyttzsta.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpagtypo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2laggkkmo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iofhhkqt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yknskfhg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjbnssc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbxbzrc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvoxzpn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hljzrdnl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmzonhs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxrcodd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2widjtaru.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pjogaowq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsmxwre.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsookecv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaeegtn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiqalpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfmveyb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxajdwup.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fitwqosd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoghsbl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdhsejf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aihxbwla.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sypvkjwt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2empfkqbe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlicjqsl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjxveyx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnakjowp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axjgnchd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjaskuu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzxolhx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oudpyeek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zruqsamg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2joifzwhi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkfcnto.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrfwnbb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2utkwqvmu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jprhzlcn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2grxlrvxq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2occydgas.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuczhjl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2klvuzumq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fchzijmb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2judqmjjr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2httpuiva.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmldenb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbolzcif.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bllouahb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shonusxx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvrsyyu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiahsoz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkkjdky.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrzpapx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sscbwdeo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbindpsi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnmjmsp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upzfbirj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaxomra.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkafhxm.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pojhascb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bakkhwui.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2njmgkozf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lytkaljh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkcfwrf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxxuard.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxzqlcl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrinnny.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgovshh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkpbvcp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyzpbnx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyvkyzp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnptauk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzfgkfs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpkebnl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbsbwbi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xilretnr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgnkbas.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzmztaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yugxhcby.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfqgxr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smsfmria.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaygpzg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfuxqjg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrjmwfs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnurhkf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyeguaq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhowlter.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpetzwz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wkstdbcd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fffnsvhg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2egonuacf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmuvxkm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvnzzcx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kokvykse.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmunwhl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iovhlqbl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aisymzdy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2icltxcix.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjlncql.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrpnsij.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kgufwdld.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zznkzdhb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdntrij.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jctjurdw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2znaohsss.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2urxterbr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcwxgfq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbkjcfo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyifbiw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvpuplc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2flbfzsju.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qhehsuxi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrjezjm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fimpvotu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2efnaicql.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuyrutr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdybamrm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmlxvvk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrmtowp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkyesxw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2thyzssbm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wrshouyz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjhlydk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2skwlprrc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpzrmix.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2efwwedka.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uifmgrsx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gnubpill.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aggehvbt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djyktvjn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2trcqwerj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aemetckm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfdsnuu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2smlrdijs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lizjtikc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjabcxj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvrvsnb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfxrbz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pagdyaqv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjftnen.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtixsff.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tptimxim.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ecivyrrt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2csykfmrp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2payxtaxm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twccmezs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxlsepm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2shcgykls.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2khttkjwj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rasjtclb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsbffhy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vahfxchh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiqikmn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoybdjx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfunaul.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfjsfnc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyolsoq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2txuvvxry.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgdddl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cemuheqx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwmbkf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvfadny.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pytysnlr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pezojnrg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gclccopb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2eruxudyz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rimolvej.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrtamby.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ebakowbi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2krudvrdb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjzftal.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mllhdygc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeuqlse.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hokuivvo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tazajwex.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2svcpjcgc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxkstdb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hnacsvlb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlofojrs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wogfbmoi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjftoag.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ydksxbus.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iuythcxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clqukidr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2acpldsph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qccrcbvh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pveuybem.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qprripgs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoiaoar.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmegeuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxtegor.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgxivee.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtptmyq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaeiqwz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrdkyfe.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlafrsf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2duqlxsto.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxarqijr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhclgfl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eggxtapa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2whphuubq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiolihi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hepfseau.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkubpjis.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwddiwy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2axnkwfqp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbkwcoi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmoliyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2otndsebf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfbbogm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjjcxwp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcupukhf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzyzqav.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2swbuvbnp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkdpenh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmjchbc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnvgyvk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjwtaqb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2drpkgfbu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2aswqkavq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2apkuojxq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvgpheq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcfypnp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqdwbei.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydirlbvq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxpezjs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvgtvhq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqsiaa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlrcvub.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lphpfklm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxhheye.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zseyltbe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwclgahh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pctqgmgv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmacicm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2srdaazxl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbpikay.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbyyfdp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nshxmzms.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyvwegg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2swctmhuy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiyospx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eurkhscf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxefnnfa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmumnkqt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pspynlnj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpzgprp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgibrkg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2giirqldc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2djtdkaol.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpxhkkz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktapmwww.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cpixibys.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adxynkkp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcsfefv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2istuayhv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2grmsiaun.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zingfmkz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mumfdmtj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkgpmte.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnigbwz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2thoycsty.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmrjnja.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmukwcx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzmemam.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2beedbipw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvgdvyq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhhzmai.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcbjyoz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bckvbpqk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdemsdzo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtcbbxt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utqbuskb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vniviium.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcntgzxg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tgavyppm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ivatrlkz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhxuamu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcaolop.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdefcwjh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfzxwie.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rshjiqjg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwybgqq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiutautg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2orljgchp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlvnquq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2siyxsdqp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2omrhugbb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmffhckr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyybsaz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfgtmxv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyyttwd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oihixeme.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwwnczg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nowzoblf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mshoccom.html


<!-- 参考信息 -->