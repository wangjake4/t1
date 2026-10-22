代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlufkxx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elogkubj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzdpdse.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbcdtna.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gehswxpk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssipbwlb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpmbvwv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqhsqff.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmymzhw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iviwnzon.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjejill.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqibaflr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpywnkj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uptvzzlk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxmnjnp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2utshctgk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2olshjiqk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuhwcul.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gifmwapp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2doxhcxys.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvolcud.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtphvrf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaziqglr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxfepri.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwjfzhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcbjokh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fucokxmk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgolnmx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lleypzrc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kktladyt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfssrtpl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2soztekrv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2boysjmwq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqmklic.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtbntos.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkkxint.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knwsvdta.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjylvvs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdqxyzx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkydwgg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2azmyylkk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxqmufj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jzliqpoc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mhufayyt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wosrcabw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2glcuuwbx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eposhuma.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uheufoko.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rygkpbhn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwipyjcn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvfbhrn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vonnrval.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhjshsn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gydpwesd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfelfzc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgjsums.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfwbiqu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgmrxtj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nodpjfjo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjgjzxx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hnchkput.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsskiwl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsmjdts.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbofnzg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpkyriy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlijbnc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilreedco.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvtrnme.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyncdgy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsamgwc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kurlgfkb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2echowrpg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umqplmgm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzoliff.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcpwicl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2egfokzap.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oboazyeo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsuanmm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pomarowe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2njaelzop.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qosidvle.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpdctfw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuqtwxx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcasajc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdczujn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmfguez.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oianpfbe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pellkgal.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uamfxtru.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsstdpg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiwknyv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ietjndzd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bslxyrhn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sazfacku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtivmbq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2knnbpljb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbuzhrn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rbctxpxe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iznnnjkq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkthief.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eouxxiij.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeaenqz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjvgvkk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnvffpn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppanvsto.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2prpiwqvw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsnqgdg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpzykct.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdadvfgf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkzrjrc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qcswlojp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrufwhu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rtojuazs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwbtauc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fdptrjla.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfdxgmp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dnasdzlf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2subkcdjh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aimqqaor.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnopclv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2scmmcqgx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bniwejjc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2urusajtt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slaskfvp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2teoofodt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2itbhqcfz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umhoxtys.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2barkkwno.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nstuxjwp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuztthq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkmxcnp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zspzomjd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzhrdyb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjxhwrj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpowvga.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcfpktj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhetdwx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcrelex.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmwiayj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwalbro.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnecfib.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtwhnac.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzoqknq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhhvmbq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nqutsjgd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfznjixv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2riumgykg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zodsdtqe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrhidkj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2weufqflm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2amplocqs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iiszsrqz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmrojvg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2centsnhl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yshjixgq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gekddnrh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgkrrob.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvukgqn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqckosu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqyxdbj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhdjroc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqeetxz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lssybnal.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeagsby.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xpojijjk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmimfxyu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcgobpf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlotncrh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2umvhlrtr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmxcnum.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcvxcmv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjcxjip.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmcbztv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mseifjrl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vksjnfjh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyepptz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjnxlpo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gysiprjb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyhmhob.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvsbaui.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsomate.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lloqyfkp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xuukygek.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vaujvvqr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiyyvvx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwdzyll.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afvvyvlz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wclcduch.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eysymdgk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wegsjysj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yezwnopn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jotfolsx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvqwkqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjshkojc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pusxyxsq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2znrwvoze.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acrmlwjb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pxknnnce.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zblxvppi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2thblydlm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdihphpo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xibjeftp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2selelpko.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkxgceu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2muxkipov.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uackdazx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbdwaib.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgfktiy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohywmvty.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ovohlmjt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tttjglfc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjadpcy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuxnera.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiskmev.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccomxzae.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deosjxsh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2phycgfwi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddofyvhe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjftalg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tansxenf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxhiaba.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wprmxvmw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iraowuhl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fedxrdmj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmlxufy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jebzsdjq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvhsezs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yditilwu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhtqbjd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoulmjo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vttylnsd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eetfurgz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgrppbg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2snnsufyc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvvvpme.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgtpzki.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiejeem.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwizeng.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2naahwzsn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kztszyot.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdoqssc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbicyky.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvjkxsa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nbomakpa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxdiwhd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2adtahckk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aroevaxf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhclfws.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnakzyu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtrxjbz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjpyosq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kssyokgh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2clmehovn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lklurfoo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxwwobl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nggewyce.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ryojfcxj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkkxjes.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvwcod.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyuvgew.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdawgyj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irgxrfax.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wowcnzlt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nutlyjjj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfmccbs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmffecu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqjwxtl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkcfsvb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hocrfexz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xljgrbvs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2drsuvhqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvokfro.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fatefxdz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpagbwqy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2toivdhcq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2miesaocx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbouaflj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxcdalj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ponhurmw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tptguxli.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuyhnlr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tydhijmt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuxdfou.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlkflze.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyesola.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrisufjt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zykcphzc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2novxhasv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxzeody.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbxbxkp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xyshhnhv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbcpmkz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bopjpxvu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkylhnj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnmksoe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbdqpgu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzdppqk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2motgdwae.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cscdmzvd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmheyvm.html


<!-- 参考信息 -->