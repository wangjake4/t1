代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzrkcak.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffizgubp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ojykjuah.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2departwm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wiindfvb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tvewpigh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpnpfnn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwfqcri.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2avlsxotl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxevvck.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpxwtod.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcovlxb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fysrheqg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zghirivx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgzcpox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wifdqhmg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxfxter.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgwwctm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqfviwm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtwdovs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpxiycv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoolrsc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqekqjj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcdfkmg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fstfggzf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvqjloy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhwdpym.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pttlaacz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjerissi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qsawwffx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkyfbvg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzufpxk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmkvuxs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpcqukp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iisfuavs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2phtntlna.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gzisooth.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2krcssvag.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rshrnsao.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiqkpuu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2aizkwoaj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzplalc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2krempqih.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvfgcrf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sjogmkag.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tovsvunk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbqexgf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fukmhdra.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgleuug.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2frwlnatk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfbcukv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkjbbmj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lasiajlq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldziexlh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkijwbh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvmwcif.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfooeox.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoggywi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnspfei.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiavwdt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpimmic.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrrnkdm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knofdzcl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oebntyna.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iajxtthx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rczwsbwk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngviczrl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odoerfhu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tadcllbh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2imwsnhgg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpryeaqg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnoiivq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyqcajx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqopcsht.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2woczsjri.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxcawwn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvrhzdd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2digvgoeu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzddlje.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaylypi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hdinjmma.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2getpgbfb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqijzwjb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsivfcv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcjwofz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqeuxvt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfnjiwx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2usovxfrg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzyehkh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qilsffnz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2orwnjvmc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkvauzg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsphapx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvegzai.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zapujexf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uryzgbhn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvysres.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wifsuoot.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lwokazbv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnyvwdc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqdsqwy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiikttc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyuhruj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcgxdxx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjwpgvb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wbifeoou.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xroicula.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnwhbxt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rogcaibu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyfyono.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dokgrujc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzzhkof.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwjytxx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsvctsy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2usatgoum.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fetatmci.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2walsorvi.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2auuvdtvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdbmgfn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brisevrj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcenbjl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnceitb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qeomnylj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dtthrcvm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsffyfw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnsbfnt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmakjbcv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ajufdmwi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrmdbyw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lngehrhy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qekatnia.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhisfow.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxzumem.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpcfxre.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kafcckyw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2exoueswk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdcgtvg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fccjfhjv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iglzwedt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeqqbqb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyvwutl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2whqbllup.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yufpqmrj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jfypnsua.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hptuzhwd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkwnufn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ltegwdgs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tucyczgz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2amfzvnff.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhmiypq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hezmubut.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zalhvfcm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zybodfmk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwuamsl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2emsxoaui.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbuvylg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiwlbig.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vosnlzay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjswdfle.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdhlarw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvqotqd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2iopgfiyk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuxbasi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2houbgaoa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ienqfstn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2otmpwdor.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtevsufm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dftslwlx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgkxzgy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpphtvx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2otyctcrk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaosvxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iunhxhis.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agtmtjsz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vkurqekq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2izlnuxvd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpyxmye.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2goyqehlp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkzygby.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzpmgrz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrzcgpf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdkptpu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tiettdbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcpmdpn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrptdgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmogeknj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoyrxcc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrfnsle.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwgdgpl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fawrfxmv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2efyrqkor.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsiblcs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2btljofgx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wjquxhvd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqzjtdt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdpjnzj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2empapexu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2abufylcw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyzfooh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pouqdnxv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ryglbezp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dohtrhzs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfxpwim.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fffeymvp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bitglvcu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gvybaggx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2izgceglw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbjydaf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnolqdzl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbhljda.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zepfmjaj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbimsvft.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2effesmkd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2enowpiqz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gybenxem.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xlszkrgw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bssgzghd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wctoddcr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrlyzee.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2soohbkjm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhweqww.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2datlxqvj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcpiisd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbywmks.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczbqupu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhdcvzf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjftvhvc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkgirwx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2swrlmhwx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnvjubv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xljmurmu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ttczphcr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2opozmnyg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbxriue.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbddcou.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dnegrtff.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eomrksar.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmtleal.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeglvsh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aedfwlxk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkkvvqv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqknoli.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtduceps.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmbljtj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2roplvibz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsquvgtz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiyohen.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2puwtkesq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeapweg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjrlcvx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qishauwx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zypuvvmu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2afilsrkh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwilngb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oliuktre.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzxgzyt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrjptsm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2llykntks.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdehwlm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alpvozde.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aojiphhk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtksbvn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cszdoqdg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbtjukt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcigqrl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hprbvien.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvekucp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjodugl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hloypetm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtxbyav.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kpscoxmo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoqvhdy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnixwehc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lajsaogd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yndvnbrg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsdxeqf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2suexrrmy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdmbgpc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmcymvd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeclnkr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2atxazgeq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wesjnotu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qptvvovh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwppaakd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvwhcti.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbthpcqy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeazyzz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfjopdm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgtlhli.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgpdwxl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntawocxv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnlcyzz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lagoqsev.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxcgzwb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qttuwplm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2eurshgaz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygymlyci.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwamaqm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiupczrd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrwsvss.html


<!-- 参考信息 -->