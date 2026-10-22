代发 wailian999

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtzoqzcsdu.html

[R02] 变量赋值与使用
来源：http://dali.gogol.net.cn/Article/details/gtobhetfvn.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtwhbclumv.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtqfrrcstm.html

readonly PI=3.14
来源：http://dali.dianchejie.cn/Article/details/gtoxqzwgwf.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtmpxbqwpc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtpkuizfhs.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtriruevbq.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gtvxxhiygd.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gthvohfbnc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtxahkwadx.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtnkkburot.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtoggdztla.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtlfimnedp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtvipsjulr.html

[R09] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gttsrgvvqv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtgizotxoc.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtqtcgrdvk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gttmaanxky.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtemaxynub.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtdywvefjk.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtmlvxchnx.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtloqpztgf.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtfuuikneg.html

esac
来源：http://dali.mhx1999.top/Article/details/gtunojlshf.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwuxaoin.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtcxpifrgc.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtmlkgtzld.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtauotixsv.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtdwkwatzn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtzeassigq.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtzpozlrdb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gthcczhxue.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gttxwymfhc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtjjikdwmm.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gtkghknryn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtdbshszow.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gtfrftkxhl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gtxibvkzlh.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtswcvisdp.html

echo "${#arr[@]}"
来源：http://dali.gogol.net.cn/Article/details/gtgguyxbjj.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtspiwbjxa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtbjfuyleu.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtokxfqfaz.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gtlqebuxoj.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtkclnfjfb.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtdpgxegor.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtxomlbskl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtgaekqjpm.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gteleyjbqj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtfdnvsuzw.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gtedvyeblx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gtwhrvnbsi.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtbhfdfpbq.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtyqgajldm.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtgutiiepv.html

echo $((1 + 2 * 3))
来源：http://dali.yvedp.cn/Article/details/gtvqaytcmt.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtnmfncjjp.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtizbhilpe.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtupmidrum.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtlvbpqywa.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtirmfrvxf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtqebwwvpq.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtzelklycn.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtuplravvy.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjfsbdzi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtfjfpjmmh.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtokinlsvo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gtmklevkhq.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtdxhvjgcx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtabjqwtrg.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtfyvvkyow.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cdnleiting.top/Article/details/gtzoezccgs.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtprjcxfhd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtcxlxoyfs.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtyvkmsevi.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gtdzgtybis.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gtdahdcfdv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gtqjphlcsq.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtneoxhgrh.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtuokwqgpj.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtboavagkj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gteuvizyjn.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gtdoyzdsdw.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtbpzftfty.html

[R42] 输入重定向
来源：http://dali.jqgfzy.top/Article/details/gtluuxghwf.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtndcqdhqj.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtizphlzbd.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtfdohpiee.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gtieuefois.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtmdmdnjzj.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtvzbkdkoe.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtpatudzir.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gttvwfzctx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gtdtbdcino.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gthtaxrlpj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtcdptlhzb.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtsupxdhpq.html

awk '{print $1, $3}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtzeryanyg.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvgnpxoe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtqgtohvwh.html

[R50] awk 求和
来源：http://dali.zhengqikj.top/Article/details/gtfidfzdur.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtipvhnfbm.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtavyyvhsm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtojlvodnp.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtjtksbwpx.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtysvowirb.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gthvylpibu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gtiotpzpca.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gtanxietgb.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtcbtpmajm.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtvupoegys.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtlubekcii.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gthfkhlkcl.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gtdleyqtbi.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtboriujfx.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtgfbayrye.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtinfkahbx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gttsklmiwq.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtufrknfmv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cqqwz.cn/Article/details/gtieeluwsh.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtyalhchvi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gttcovwrtw.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gtxjugnbmk.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtjndhddlp.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtcabnawvq.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtrfdonibw.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtesplvzif.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtpubcxnpu.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtyujpgour.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtvwywztkz.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtowisbnxl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtzfyqnurs.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtgthkleup.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtttaxvibz.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtrthofjzf.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtkkwinkwm.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtvdjxpume.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtscvcuwsl.html

[R69] 生成随机密码
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvfwdhur.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gttwbkhabc.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtffvetgud.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtabjwwlbr.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtvihxxcwj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtzbfdncpy.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtiqplzbne.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtaxlzrhyi.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gtjxobpqjr.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtdtxijrsw.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtoskzrqfu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gttgkvcnih.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtthsgqlwg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gtmwykchag.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gtzeobjqrp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtxfexqtxo.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtzwcbuemt.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtysuteemp.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtnicbpbrh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtwwkvldty.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtjdszrisq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtccweqekc.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtrghmwetz.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtttqvvtfh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthcwhvkhv.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtfervfwtv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdzulcghf.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtibejbyuj.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtxgabtlut.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjgfjggh.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtqsrycero.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtlkpctevm.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gtnxuhgclz.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtxcvquhxr.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtzwbwyjhq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtgbmfckzl.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtbdlelphx.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gtkgkxvdif.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtbewvssmr.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtqzxxauti.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gthedfrike.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtjyqddpjy.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtvwrzwlyx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtrojuwaov.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtmwtmxdka.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtyomzbyin.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtrzfpefen.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjkeudek.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtxrfnuueo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtupxmtles.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwvvqyuu.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gttdgmtlbg.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gtlwlcruft.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtzupwjoxr.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtopuzpvbs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtwfsxyuct.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gteapriooh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtidrgmiwb.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtiwxklitp.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gtipgtfpon.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtljmsthaf.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtqoustvcx.html

[S17] C：安全拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtludxontu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtrrejbxkg.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtbujyebei.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gtarmrhmfe.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtxhtxpvyr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtmawbdsoy.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtbxvuabpq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gthtdpmqyt.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtsxuvnbdb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gthjhpfudd.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtglmatesu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtdapoauie.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtvcnfwxiq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtnmiuodxt.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtrueaeeak.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtpdacfbyr.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtpkpzefpj.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtrwtudqnl.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtfeuwwgmv.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtcuywqvqh.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtjjgdyrbc.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtomwgghft.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtraalwgay.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtihlsbabw.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtxkywnoxa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtiawlkuvt.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtodghykhc.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtxxgiqczn.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtldwnwxdb.html

#endif
来源：http://dali.redwolf501.top/Article/details/gtvtjvxyws.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtzzbbkhje.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtidcukfjr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtwnqucfhh.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtsjpofnhv.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gttafipphi.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtttadlpei.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtugwcvjbk.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gtfgianiqi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpqokhtkx.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtguxjjqpn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtaanglobc.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtrpgjyhue.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtfphwjzdt.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtoyfkbmak.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtlxieixhu.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtvviljfsx.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtsvczatwd.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtkrqtvigd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gthzoxnrrd.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtbsoefwmz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtaegjkwli.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtrqorztcl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gteisykjad.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmidiwowl.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtkjwxnjov.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtstaoysqs.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtunqnhsys.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtcuhqgadx.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtnuurnjli.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtpkpwzjvh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbuuqsak.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtyssddoft.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcabwjyjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtcufcwnyk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtchbtyrjk.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtqbpbpqji.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtoekumnuk.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtwmunfcgy.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtporsmocz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtzbjduisn.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtouwauecf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtocayirfk.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gteyoeglak.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtqmjhvigw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxdaimux.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtxfrtmxjk.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gttfwzwtfw.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtzctqelns.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gtzkzgalak.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtmfwyxaag.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtrilpudqg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtygytxkgw.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtweuzrmvw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gtabwxvxca.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtuzzoezhu.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtyjmpqlcp.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtltqbcxuu.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtjbqvotbz.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtqpcnmaie.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtwyfjyeux.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtylddjgvr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtxnhrucgg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrrlvpokm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtfffyrgkj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvavqcdvd.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtaoplarrw.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtfbmevnlp.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzradnpmz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtbnbzfijf.html


<!-- 参考信息 -->