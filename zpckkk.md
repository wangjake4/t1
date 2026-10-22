代发 wailian999

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2osukdxgp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcznbjq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxaeknz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaryxfk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jziixggy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alxfikby.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2slizqgiv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcjkdwp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuihwbgr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qukwfjor.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyukxrdr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txhhazkb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdgepwq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afzpzgpt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxosmbt.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rfokkoib.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwoqgit.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2opjfgoao.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeggweh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vslmtjqm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuefeog.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyynphhi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hagzccxp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpytggsw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwifzgw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbkqaxj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onjzzmpa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ilulxayz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srstaowl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ktikxkhd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ciymreyb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cceakvfp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvcxbfv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bopojehf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrtotlr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdtemjk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2laqxqmng.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mdckssdy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzouvgy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjloogvc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbhdjkm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsbpdnp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2evbvgfgz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gomjeenj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnwtnze.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqugucsb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iztmfiks.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdplugh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfhmyzy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpiufrn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kanmvnxj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2byshitlv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2esniuogw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbctmdep.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jumhrzjq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoeaawo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzhtaxh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pphuwoxb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oywzoaji.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvgivti.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vymtkfrs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuhkmkt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aipsjhkd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hirbshzs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgrngyi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzfilaa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jayhmsii.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pepkphnn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlolosx.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtviogt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nruikcha.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvoosik.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2llztkjfd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owcbpfwv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqctsmu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwkopoz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaunugid.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqohurj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqbluhc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbitpqn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdvueou.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwetwno.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxvwpcf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2crgcjitg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2psnhevst.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmqqosh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeshlyj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2solcddbd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2avsoarbc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxwham.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rqazyova.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2arbumxdh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rshqqrbp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfwxdvl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpxxgqy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxdrros.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhtiwam.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhmllvg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dgglkydq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yewmychr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjkdchh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiexldv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oagaimeh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yqubktjf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpsvvxm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2irctckdo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmhtcxp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvraprz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2krnlktuf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azsxvohy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gydujjiu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlmrvco.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhragfy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jrokdomw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbcwjti.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xvstubgs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiwkajj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhsqija.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hctsrlkk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2idheispx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zutzzdbr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jburvcwn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jajhujrm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwvexch.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2apyxfitc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnohnlfm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ongkugfu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oepwdhrc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdurbvw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2evezrqvo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrbtcgu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2omdeiozr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwjckfd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifripeiy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gxohzqpt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlfumib.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wfenuyap.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fytcwgjn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhxpilh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmbtidf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yiangbxe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nubehvsp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhooobf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrkcgkx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2shhpnnxj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2awyeojfu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtqsiyb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qlilirdx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eivqqpni.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxndaww.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfcffkj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rayhvdzv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrjxlxf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enmqibkf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpsnfhx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpemeez.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxgnzdn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnwjzkn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsbfxcp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2swjxllrb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fieoofqm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2diehuxsd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2annzofmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfbochu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yovwgvij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkihrlc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdukjzlk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2byirrgak.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzztvuc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ofauxacj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wloqfscd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwnxzxi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbpntmp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmqiumu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyknpten.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpbntkl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmzpezl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yibgqytm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbzkyxq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuxmmpy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gahgqnog.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nfczqmsf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwopwexh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2llkbtuqs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoxvcmt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kerimftd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeabzvho.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csltanpj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qktfihri.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gezklpds.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dflratpj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sveuvyro.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkscjmfl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2avxzrlbx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmhpwil.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wiukgwqi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsevjwoh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjogssya.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzbljdp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hihdkvdd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyodksli.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnixagdi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2scumdivl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwjkmxg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrhykac.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2omjeioga.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bacucchh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfhwqwn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nveaucsh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtczepx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qccpbdpj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vzujflif.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiurskf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2apqmqrjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2estmyrer.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mdypaosn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjpsgpj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxxumdc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfbvlgu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ozixwxqm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xikmzmlv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqglbmhw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkfdqga.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nblvzlvo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2luqpqhsx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sszupran.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2faggajzo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjjfymj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwvazfz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkfrifk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjwnocf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpiqjrj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqfplan.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlwnyry.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rignjmfl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlmqxqe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmstoci.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcttyivn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2porusloh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drsidlxd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cppclygz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfmesne.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfmsqvc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfdyzxq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvcmqbz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfepmcmn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2enrjmmsg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uohdkkth.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vkixdjvj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iixbtzgk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2czvfkfld.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2abubkrxr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcfeicw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gahgvazu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxemhhm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvsvhjs.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nplzuksu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2akxbarvc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvzgiyt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpshnri.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcrzjqg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmbkirv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2akyoitze.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiqzwyx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyunbmm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfiskri.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btmtqdup.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuezrue.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzgiost.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzarlgkd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvngxtx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpwkzop.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegawzio.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dimgnkct.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ughxzdos.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbneowc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yksztzbm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkeclpt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoktqlio.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlyizia.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjecfmni.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2enubmavo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyttdjvt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pszexmlv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owwugyyy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqwjfxw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfitakgx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbofxyps.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkknuad.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcfmsos.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2omxvkifi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rptkngja.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgqltdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvevqij.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqfvtjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhwrltk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iybflvjl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2udrujhid.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlqzsdc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2trukxyre.html


<!-- 参考信息 -->