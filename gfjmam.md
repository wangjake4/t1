代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqeklxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oofwrheq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2soojpavz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wasfgckl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2laquujaw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sccmjcci.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wamjfcqe.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlihibdn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2oqirbwmi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxyvqom.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuxywtl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eaajhqwc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nieajbff.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqxxqjg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coefxebd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wekznwzu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwpekwf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrxctig.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmntzsp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdpebna.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2daycepne.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wqupiuaj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wezuipnd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rknclbki.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqywbyd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucntkumx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2znzsipzk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwecyezh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nayieged.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmtanri.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrzyupv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sawolkbm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwhrzku.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zviycxmm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaccjda.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrklgrhp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfalcst.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2peuvsimb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzryomle.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewddmurx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2choxyveg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2abcoybis.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpncclyw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rlejxnjn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyadehb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrkwrnt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkglgyq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmvhbmp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gutcfhkm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewujizff.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2denzdcuk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfidkpux.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmukyiyv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcisltld.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqhzvbv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ovluvkpo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2isrbsqpt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvfonxg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjuthkz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2axtsfuhp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2amebbvhc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkgekyg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iyudsnpl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzivxcyr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yqylozih.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxknyer.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwplcmac.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoksrfh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paddychj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rafylklh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkmowdg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wnosesdb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwydmdt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oaczeseh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fxttbjfb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2esdepkav.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2boavbjnp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iabthbew.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gktafcqe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2utsxftog.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhrdiay.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlrqkvu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvgmayc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2amuoobvi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgzbpug.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdpbvvu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rblzpgfl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpshbvp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsigylu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqaqbsf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcrlncm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chplrbpu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hryuxnhd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jjugfojc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyzxqxt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2maefihez.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2plwgxojx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2olyvnyix.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpencsue.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kagwnjiu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzzlyil.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtnsxbz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzuvbqd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgeheyx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrwlhfw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nviucltb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdigjhyk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtqfej.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2finlhbzs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2skqvhkxg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrtnuce.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yinigtlt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhnllxy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzprldnw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egqfjmjt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hclzvzls.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2htrmnklo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2idkugjpk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbybkgo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jcghvfcl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkksahl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkupnad.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbamloq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxsavzw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmpdhbg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfhlzhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dqentsoz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2duwhtops.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2prhsmiuv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaixjyfh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxsxxde.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nwufwtdw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrjtqeu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoqzmnf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2eabcyxwf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mzebqnfg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dohdeedo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2amwjzsmv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rslsftgi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnovzibl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2onnupvjg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaqvzhq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tidessar.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlyxbto.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fapvmkmw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lbszvqxv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2swbllvpx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvjsnqk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztibsaok.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsjpjlf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqpwejc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhswynh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2htinvkkc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rnepwrlx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2erdkbftr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anwuvkca.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgknfzf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etanptam.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuehfwa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbubjpn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2phbmgmfk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrggksv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2matqocmu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxjumti.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2frghhpfw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2glbpxpij.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbiajmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcolxmwv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhuskqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwkwreo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrpxvmg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqiyfpz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvrtirc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ibokivtk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcavftha.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlpuvdk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhttycol.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdmiovd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2smpjsfmz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2emgbvskm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uopjssqc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkhpscy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tedtpbyl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxostff.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdommeg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmjkhws.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqmtoly.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjrptkw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkiafcv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjnfyvp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcoxkcw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnylbtt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2glfkyyqa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrnnint.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqmgyck.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvlhioa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcsjcar.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mlujjhmf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzhnuoi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2whqonjhb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahizwkzq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytackqwj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gscljqyq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yjndhcvx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxpztmt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amrwhpqt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyihfnls.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqafyxef.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxhshgi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ohimwyph.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtztlavk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gshoiddu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtmfaew.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wultlmjw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2soyluoel.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2igayqovz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayavkogr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2posnbttj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilekypsu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqumftv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmanjlmh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rfndqsbm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkgrjcd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oagdvphf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mslimqeh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2thaayben.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnssewx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwejqlcv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrunzkv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmcthvm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2irgwxccu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dpruapog.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxtdswa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2npqxouog.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwipjpo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrazbkf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2edwiqrfb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tffspqbk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuqguug.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwqqzrt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2avyrhkgk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbovrrx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbpmunc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlribeq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzejyfe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2drfawtrx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvnwcxn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2byjjleec.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwpuclg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgceesh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfbedwp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyzkopm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vubhtfhf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpzavht.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2legqjyxw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2euuznuei.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbymjab.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtioqzx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmebyzvd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnswtza.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbznbof.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpehhxg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2giixcvae.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvbtywt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wuugkczh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiunnno.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdcepev.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvwvcqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrqngjk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stsxhwjo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alxjwisl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2choozcpp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngriagdp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jntaqimi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2opzymzyq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2whcqasfl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgblyqdg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bythndac.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtmayww.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcswzjz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjggqra.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ylypylue.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbmseig.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2liwmnvgx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2worpdukc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aysenwej.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pswnpzsx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpgnwqh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sydrlpec.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lweypslm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nscahlhi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2epgwrirt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2abrssesl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaurpvm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdullyz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzasrxj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bnahxlkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axkxpmpv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rujvesqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqywfvf.html


<!-- 参考信息 -->