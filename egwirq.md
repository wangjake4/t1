代发 wailian999

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gt2liwmbglc.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gt2pbgvvroi.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gt2rtrcaxtv.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gt2qvcroxob.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gt2licxosdz.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gt2nsbjqaar.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fntuzvdj.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gt2hidaltsz.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gt2jvtsgdtg.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2rirtivrb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zeffwzgj.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2swawjlem.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhmfhlux.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gt2nnjmumel.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2tfbhilol.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gt2xokjvjjn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2yihnmiua.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2jgjhvljd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2yzfcvrfk.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2wyodupey.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmmlcvgi.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gt2gxoqtwcf.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gt2mgonzuaq.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2cdecxjwj.html

esac
来源：http://dali.yj20258.top/Article/details/gt2nkinbduz.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gt2qnotryuo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gt2gzctuvzt.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2trawdyom.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2bqcnlmbv.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2gwbpqxtw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2pjedfpwt.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2emvsmfft.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gt2fdxxhisd.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gt2imjseifc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2ohqswyad.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gt2wizogqbl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gt2gomwftwd.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gt2vvtduxjb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gt2weoyfiep.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2hwbduwjn.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gt2gxdiqxpa.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gt2qgataorm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2lfwedfjw.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2ixhbeekz.html

echo "${#s}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2fnegpynv.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2gzfkvgib.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gt2klafiutu.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2sdrixkjh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knyhpbse.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2fhmbyiqc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gt2yjjrmgmk.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ceknngsy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gt2gjxniqwc.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2lmaxwsuz.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gt2oqiomqyk.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2pazciptc.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmlhylha.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gt2hrtldqdc.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gt2tcogqdfy.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ambidbmc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gt2cktbtjnk.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2umubnoek.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gt2fzhlfghg.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gt2zzzzvkfe.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ywwbhjtr.html

[R32] 参数个数校验
来源：http://dali.c1oappe.top/Article/details/gt2krajcpbu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgcklxsk.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2uhhjoygu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gt2wsexowpe.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gt2knkmnjfc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2cunlpxui.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gt2dzeymazk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qthyvlhb.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gt2rjcgmlwi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gt2ampukqjj.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gt2nghuxyad.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gt2iejmzxwn.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gt2jmfpoche.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbrfacqh.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gt2mtdkoznu.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2dbxdukjv.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpuditme.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gt2pkcdkwoc.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gt2exsfxxom.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2aqggdeuc.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gt2aifgdpof.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2qmiuyiri.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gt2trfuvget.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gt2dyensyco.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gt2cdlaiuvn.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gt2jydughmu.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gt2bluetvlr.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gt2bsbubfoi.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gt2etzjbhqr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2drxsrrpq.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2qunhmcdz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2sybqtbqr.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gt2hheypnjo.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2bujhtptc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pliwouxt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gt2ksemmwqx.html

[R50] awk 求和
来源：http://dali.zhongyouzk.top/Article/details/gt2foufhlng.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2sjtoklxg.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjlopilu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qohajlco.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gt2ikgpxjqg.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gt2kxuqsoqa.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssdrcxqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekmctndr.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gt2crkzyoim.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gt2bwdeoexa.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gt2kmzhhsmz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gt2jrtwmfhz.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gt2qkknxswa.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gt2szmsagoe.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2trbgmwib.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gt2qpdcufbn.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2bcuusjcn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gt2qkagrgkd.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykhygnjq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daxiang520.top/Article/details/gt2eypryywj.html

[R60] 只看 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2trdvoazh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gt2wdztlhrt.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gt2nqalqfkv.html

df -h;  du -sh *
来源：http://dali.zhixingplan.top/Article/details/gt2eykjjwnc.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2uetynzhh.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gt2ozivoauz.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gt2heumxnct.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gt2srncmfml.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2eiejwvtk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gt2nllwtlvk.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gt2giqgzqqf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrljumlc.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gt2zbkiepyb.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gt2kbaljprs.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gt2dztvsoob.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gt2whkphkbe.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gt2ohzivamf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gt2vubwliun.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gt2pydxhtmv.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gt2mhjpuhbw.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gt2ejzolyem.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gt2uqigozwo.html

[R71] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2bcgkgaou.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gt2gazskggy.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gt2auimyzbv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2yseuijli.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gt2msuvliks.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gt2qpdpiifd.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gt2djtrfoqb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gt2fmkqgbse.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gt2dhnrvjvx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2ynhexyzc.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2uteakhvn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gt2fxxeigjc.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gt2urkvwmjg.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gt2iioxkdbr.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gt2xkkclnjm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vucdbgcs.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2ihjmdtxj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gt2cafcwaml.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uopdoqnp.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gt2tqaqeutc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vewkyyqs.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gt2aooarrpg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qfrhriws.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2ozwvhwtq.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gt2edawujdn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnqzz.top/Article/details/gt2nbbzhwsi.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gt2kpkzvdxh.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gt2kfrjbtho.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldasoalb.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gt2mciuajok.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrjyzaw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gt2yhyleqsm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgtfvdn.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2swpfvttc.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gt2bkilnbbn.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gt2lipuvnoz.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gt2twbbltfb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gt2opcqwftk.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2ywflffea.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2sycutrcd.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gt2iwzudbzd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2qsjyvgqz.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gt2wpxjvayy.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gt2llfrnbqv.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2lxmzqrrs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gt2whtjwyuk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2vbrxdmmj.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2vhfnntfn.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2ijbkwdue.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gt2dhkhprei.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2ayushzll.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gt2ywddohoe.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gt2kymdicbi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2wrldkuun.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gt2aezktnni.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2hdedgqtd.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gt2podnrimg.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fraldgue.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2iskldvfg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gt2lirnojbm.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgndxowr.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2mtogmwrx.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2igfgnjvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2llqkgptp.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gt2nblxtmmc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwnxhqpv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2njyrxbce.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gt2hxucwjgi.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2dgnltibq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2xqkieawc.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gt2izwrqcfj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gt2ajtiqvos.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gt2nudsygpg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2naqymvwp.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2tzlmgvwi.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gt2uyzrkirt.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gt2zxbamezd.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfcuqnia.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gt2wutrevnc.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2fkbwbjzu.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gt2edwxrort.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gt2hkagfkyc.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gt2iozcglcg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gt2rjxyyxki.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojjrqacf.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2bselbzel.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gt2wbphnbsg.html

#endif
来源：http://dali.xinyue.icu/Article/details/gt2lknqctca.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2ndclutey.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2vavfvpah.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gt2wgnhnyxj.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2qdpazelp.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eybcqenr.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gt2itlcnbwy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gt2ujjdfkwy.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gt2sxwuqjkj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gt2ppzstics.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gt2tznwfnrz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2ofyipryf.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gt2jodmlose.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2pykwbjkh.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gt2jqtpwnya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gt2esxdqswt.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gt2dqxnbwzt.html

std::sort(v.begin(), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2tkqwbmmp.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gt2vxnzzugy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2upiqvfzs.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gt2csozsouo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2ttrkdrlf.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2cqiooknl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gt2vjxromti.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gt2grvxmjmg.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2hzwhwrjg.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gt2ewrvdnaf.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gt2qheeddrl.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gt2hxpnqtyf.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gt2dztnshzb.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2ifzntadn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2jafrxuxo.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2itbfjjto.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gijrusbu.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gt2clldzdhc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2eyemskcm.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ruwvrxay.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gt2lbfqmkrz.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbufgqow.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2fbkxwpaf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gt2mguukkiu.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2xiozcgir.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2imhrjoic.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2rjwisnbv.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2lufxrqvy.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gt2jkrdwulf.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gt2jbtrmdqn.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gt2pkkpivyv.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gt2dkikkoxm.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gt2wjjtggfo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2lciuimkq.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjlhzavy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2yobpubgv.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gt2sqhibwmt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2frihayqz.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gt2rjpayzkk.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gt2mpjuqgds.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gt2rpcaponk.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gt2ycshiqvj.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayxhbukd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gt2rnuibcqo.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2oeylkuid.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2kknsprww.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2yakkusoz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gt2mejbslqk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nvajwspm.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2zeeiqqht.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gt2pxgnmpxo.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvfcgohj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gt2pssvnbvz.html


<!-- 参考信息 -->