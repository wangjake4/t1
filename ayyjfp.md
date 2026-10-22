代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ossfgtsz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jswehcrl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiaatvb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdrtfer.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hceysyic.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhizmoq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zsezungo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbwksfx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfosjbj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oztgnilq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aopmospu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2omgpmtpi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvaqcxp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aytikuax.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnfezcl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuljyfh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2laxjbatc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoovavf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xidnmivy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwdotph.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efhpleub.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxiynly.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avkqwsiw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckafqbtz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjsfmoz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kobnnxhb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgdufon.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kengiouj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwahylf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfftpunz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxkdhop.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2prhcmidk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2glzhudgo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2alkkypvf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2novmhgjj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdarsdo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hozzuqem.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvegzohn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dehjlmpi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjbbtse.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pydrnthx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tafaylcb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2csjhezvp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzmkpjp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2brgsibjw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2klancsuc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dslorzkb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zscxsich.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpinelq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fznrbmur.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyiiywm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plxzcggo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixkwkm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tugkaysc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjquwlr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfiyydm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2czynyeey.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxnqdce.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkczacs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zfylevrn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxvcwoo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbnyhma.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxadywq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmjrnmg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhogbws.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gfczgqzm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxtqpid.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ixabmpbx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrkcxfg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoqrnyh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqotvex.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wprovgoa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aodiqujs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jsssevgh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2utqshrwx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fncwcsmd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtnllg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoevxpk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdezxzp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2foacpdfl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvqwllg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrzudpn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsdvnmp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlsdofp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xwplgatl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2omcoxlma.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhzgjry.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mokhopuv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmtcncq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnsohup.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqifdoxi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmemmhr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gulgorpe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jakttsnq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdydwti.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmkxsdz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eadczwjm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rslcuteq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2suymgjaz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnllhod.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jiycpmsc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnvtafs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlhqfzk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrmtgqs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhmwsao.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjiuamv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bveszqre.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nhypywnh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2djvwuccp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxvbtvs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwqholi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbbfyiz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwdildd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnbdlch.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2euqwsllo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqvcwfa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmkgfgi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaomggw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeycxhm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkevzzkt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2amejxmyg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2swkoiqse.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrbxycv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2myyegjfk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pohzkuyi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmebviqa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpildlt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2utiuamlm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aisxgnfo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hajuosug.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2apgztfck.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpnfuua.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhlcsaa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2salyncut.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwhdvsd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2erigmgwg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2midfdycb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2subjrgmf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbbgbnm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxkitvz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwrtqzq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chqglahc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dduanwpg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyyiqhu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqztfqe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlellin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtelswkb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzpcuao.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2stsdvmfw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhqxerd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqcdnlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjfzcme.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlkfbwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdxgvod.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvqesgo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfzbtqd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwzjuhg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ploiigjy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bellnstx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dinbrblg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wahxlumc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjqqmpx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2abmpdwfy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqbqmuy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrywdlfv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2swikvcyi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyluqop.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuyvjov.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtnsfbm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wepkcqtc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsvxpit.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vehrlnwh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeozjbx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sefqecbw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvkxhli.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdfzcnp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenxoso.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2incjntag.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnagvujh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvjmgqd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2usxvgrxi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cplhtcjv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zazwwnlm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2geagisdm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqswqyv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcrcgjc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuhdrzy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2unbcvdvl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bolddrhf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ufitxdvj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpyzssn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgheqhs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezunifud.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2itzyftvv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhacuuye.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2egacypkq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2swzhekiw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2btxlgsdf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiqmufz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2veceubfo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrxpbpm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aykkfplw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjmcyqk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrxxxnh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpqqijz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dmazlnge.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxekyni.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxvbvzi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2epahscdg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvhiwuq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaertuj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clvudkzl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdxujaa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtsyuby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpzfxav.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qounlyqn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxbaffl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xeukpejl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnoxwoc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ephjpsas.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mecptkij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxktzkw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrphxtqd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yafymflh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fcghxexq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwmmdzn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvwguyy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrlytew.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsqqcqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsffvgfv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfljoca.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcihusy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2igukecnj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2csdmlqup.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jrejadqz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwjjcfd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcdqkrn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2chlocqvb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2omtgdxxq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2enduuaxp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhzokai.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwnvyjd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtjnvjh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtzalus.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dpczaibp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iirdppvr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kmladvzb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqrrbdf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lcznpexb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpboenu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2apqnhqko.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtibnxqz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdbrero.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxtsurw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuddoyfq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtojnl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmskgat.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsaslnn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoeamhq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbisvww.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbvrqmm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jaikqfwo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoufuyw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fooxnpmy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkijdsql.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tysqodgl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2snqpsrhr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfcxsry.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhonknr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxsjdnl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbifemd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyibwpe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaixusg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2myvacdii.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyzsswp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnedcat.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvdzckt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2swqjqjyx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfchmdov.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgmjpcm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zwruqclc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuljwho.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cppletes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqjvfej.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjmxqvl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmnvsrk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2orysmjki.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2scgxvtoy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmlgwfu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qatflfgf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdvhlwy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xuucgedi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hppqcjud.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxythre.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmczvge.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcthkdls.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiywevx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dovxqjie.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvtdbjf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwwydit.html


<!-- 参考信息 -->