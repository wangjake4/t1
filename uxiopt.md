代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fbncumoc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2djwzjbpy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqamald.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvktakc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2asdzquhc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdliuipi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiuwhkf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nloidgmf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhigpdy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxhysn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiyptrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vislfldm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvrxkla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qojvcfch.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2etlhadna.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zunefqwf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2aazkcnpv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdybxlc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxxkiav.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtveqcxn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhlgdjn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrzdlwm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2znsodfmr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cebgrisc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scnwctld.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqvejhr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eueiznys.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbptqje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jxonyhxr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnrjnbr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bakbdwbq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjssnjk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzyvmxn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeuzsdx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaikint.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vqavrkdj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2befloijx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzhbuas.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdappnyh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtkpnvu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wgckdeuy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsazfpak.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxhodfy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dacczshn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyzwpsp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdpdwbk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxvsnsv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asuygldp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cezmigwb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilagmjcx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psnedsgu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cunltife.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qntatvbt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdlrnfg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrdsaea.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhtkjle.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpogyxi.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2quyejslh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaftacq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2utixcgby.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwkcdvj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cahrruxu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epoyycgn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iphhkyar.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbvulur.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2htjxegrm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoyoaxq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lisvmsvg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjnekra.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkmqflm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aximoivc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmtcdec.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcljmcn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hayfmmqf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2moasavxd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvtkgaj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyiwdvp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bokkvjdb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2runvjhzj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbmophy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpezlam.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqwrcam.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfopvpsk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2czymcnbe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaengjv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjhmglj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2roxpbunj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bgorygkj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2litrhnyi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnibohl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2taumzagq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqupnhgd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bowujurd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2brxstpgq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2suvmkqfs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xtapuekj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fynjylth.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gblelrih.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkzekey.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dojanqwc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpkpkvz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pbigmpbh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtypceb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfofnxnr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxdcqet.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iarvhocz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oygzovgh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpuqscy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uosthonx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uplufmaf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwkgilb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idxfdlfu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryznrsah.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfnsyga.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjeqhee.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiebeyym.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcgpncm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2woemvtab.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdxcxcn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wcetknkk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvkmblm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffknipdg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeezqvf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2drozsfmb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvtbzvr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyklwouw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbszxxan.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwawcla.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2eljtzazo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpbynwi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zaullopc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxvfnby.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnvfmop.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfijcwcu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhusdse.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2epjnnpor.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oussvrzi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rokxyxpd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pmipciik.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgfknpd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2spsprehn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jssgitwd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlzvfyt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eprkisba.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlecamd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrotakx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqfeaan.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lnacunsk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxldchs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfukrpmq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jggwfqyz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2stvjhcce.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2plrsvnxs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2alotzwly.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmaxdun.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hafozhqc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tiurdnvo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2igmplozm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrhwshm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2munvnjna.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhryhms.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjoryax.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2waxdoyen.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcphjkx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2awzyhfeg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2swzeatzh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlonbvxf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcxcbng.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2orresehr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orhomold.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2maktmeao.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvhqmql.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2brftkcwr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkhykkh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkflxmbj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pidrzxqu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cppsujfu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pesgbvnj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2scshscyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqysxug.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vbukrbqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dovgqupi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiegjsc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjhucfm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suiuigil.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zyakyrlz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjumzsya.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rokbqdpm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2apqmayjz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2slezpwuc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoowsjhf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bycttumo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgadgwo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wavnresa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yapfshva.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhtpmrd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyyhbre.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zukrrmxi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjscdhq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgpcrbd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbgozhk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2btondnoj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrljwtir.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaeoskm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhailjr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtqeepp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tatvhigh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cacramaf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2drjjjcal.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dikxcocu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncechrnx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dybnsprw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eettstpz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwahaul.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2winawzln.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2waztsstk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2atjkrqgd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hilifdyk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjthqpi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvxfimp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehsepni.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krdkrgsy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjopisc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jihorxsh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzlxhba.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wheizrjz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrghayiu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuyvumr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbzrwhf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2basyeweq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcwrwcd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nrclpifj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2oemfbyra.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2biccoxsp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2cixxpnxb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2eeokwrjr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kghsnhno.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eecrhltr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxevbqif.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2spvdzkwl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxraahrj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqirtee.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2csmfvjce.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrgudqp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2owwfrrsr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbsfiyv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tofaewzd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjbplly.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xunkebvq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyybbyox.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbwenfq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcbxbyu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gobcjbco.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2itsatctp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tirmowhg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crrwefjv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bqprvdfl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlthbqym.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2emdqwelz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxazdvwj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2egjinnhc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wltnhsoa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srrkthcc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2swqclnvx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjmcpkg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xhivkesb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kutijfte.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsxvrsq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dinkhabo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrpgwxf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpowojub.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrazloo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eylsktij.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqnmrjf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dfslgbma.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyxhyfj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2utlerlol.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcxfnxh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jayhjike.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utcnadaf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hubkjrww.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szssqmzg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxlxzop.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcmhznd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2srqyhtfo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mirqlbny.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2unzlbmts.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnmtixv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtntjlb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrucakld.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwnhbfw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbrmpdf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmigooot.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2muzsscjy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoonurfu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tetxylii.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjgmtdl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kscgjrkj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hngfdsbp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhpfgar.html


<!-- 参考信息 -->